# Portfolio V1 - Deployment

This repository contains the V1 version of Hariharan S's portfolio website.

## Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions.

### Live URL
- **Custom Domain**: https://v1.aigamer.dev
- **GitHub Pages**: https://aigamer-dev.github.io/portfolio-v1/

## Setup Instructions

### 1. Repository Setup
1. Create a private repository: `aigamer-dev/portfolio-v1`
2. Push this code to the repository

### 2. GitHub Pages Configuration
1. Go to repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: `gh-pages` / `root`
4. Save

### 3. Custom Domain Setup
1. In your DNS provider, add a CNAME record:
   - Name: `v1`
   - Value: `aigamer-dev.github.io`
2. In repository Settings → Pages → Custom domain
   - Enter: `v1.aigamer.dev`
   - Check "Enforce HTTPS"

### 4. Deploy
Push to the `main` branch and GitHub Actions will automatically deploy.

## Local Development

Since this is a static HTML site, you can open `index.html` directly in a browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

## Structure

```
.
├── index.html          # Main HTML file
├── css/               # Stylesheets (if any local)
├── js/                # JavaScript files (if any local)
├── img/               # Images (if any local)
├── CNAME              # Custom domain configuration
└── .github/
    └── workflows/
        └── deploy.yml # GitHub Actions deployment workflow
```

## Note

This version uses CDN-hosted assets for most resources. Local assets (if any) are in their respective directories.
