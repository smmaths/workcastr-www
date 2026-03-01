# Workcastr Marketing Website

Static marketing and landing page for [Workcastr](https://workcastr.com) – time tracking and reporting.

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- Bootstrap 5 (CDN)
- Inter font (Google Fonts)

## Local Development

1. Clone the repository.
2. Open `index.html` in a browser, or serve the directory with any static file server:

   ```bash
   # Using Python
   python3 -m http.server 8080

   # Using Node.js (npx)
   npx serve .
   ```

3. Visit `http://localhost:8080` (or the port your server uses).

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages** in the repository.
3. Under **Source**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` as the folder.
5. Save. GitHub will build and serve the site.

The site will be available at `https://<username>.github.io/<repo-name>/` or your custom domain if configured.

## Project Structure

```
workcastr-www/
├── index.html          # Main landing page
├── assets/
│   ├── css/
│   │   └── style.css   # Custom styles
│   ├── images/        # Images and assets
│   └── js/
│       └── main.js    # Custom JavaScript
└── README.md
```

## Asset Paths

All asset paths are relative (e.g. `assets/css/style.css`), so they resolve correctly on GitHub Pages when the site is served from the repository root.
