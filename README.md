# Wedding Website

This repository contains a static wedding website (HTML/CSS/assets).

## Host it on GitHub Pages (recommended)

This repo is configured to deploy automatically to **GitHub Pages** on every push to the `main` branch via GitHub Actions (`.github/workflows/pages.yml`).

### One-time GitHub settings

1. Go to **GitHub repo → Settings → Pages**
2. Under **Build and deployment**
   - **Source**: select **GitHub Actions**

After that, your site will be available at:
- `https://<your-username>.github.io/<repo-name>/`

## Local preview

Open `index.html` directly in your browser, or run a simple local server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.


