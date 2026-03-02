# Bharat Lead Summit 2026 - Website Clone

A static clone of [bharatleadsummit.com](https://bharatleadsummit.com/).

## Structure

```
public/
├── index.html          # Main HTML entry point
├── favicon.ico
├── _redirects          # Netlify SPA routing
├── assets/
│   └── index-de_vJlJ8.js   # React app bundle
└── images/
    ├── core/
    ├── speakers/
    ├── committee/
    ├── gallery/
    ├── leadership/
    └── partners/
```

## Deployment

This site is configured for Netlify deployment. Simply connect this repository to Netlify and it will auto-deploy.

### Manual deployment
You can also serve the `public/` folder with any static file server:
```
npx serve public
```
