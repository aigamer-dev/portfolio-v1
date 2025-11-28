# Portfolio V1 - AIGAMER

This is my first version portfolio website. I originally created this site in 2020 as a Django project, but later converted it to a static HTML site using CDN-hosted assets for simplicity and performance.

The Page is deployed via GitHub Pages, and mapped to the custom domain `v1.aigamer.dev`.

## Structure

```tree
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
