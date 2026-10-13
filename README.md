# TujjarBook — Website & Privacy Policy

Static website for the **TujjarBook (دفتر التجار)** Android app.

## Contents
- `index.html` — Landing page (Arabic, RTL)
- `privacy.html` — Privacy Policy (Arabic + English), required for Google Play
- `assets/css/style.css` — Shared stylesheet

## Deployment (GitHub Pages)
1. Push this folder to a GitHub repository.
2. In the repository: **Settings → Pages**.
3. Under **Build and deployment**, set **Source = Deploy from a branch**,
   **Branch = main**, **Folder = / (root)**.
4. Save. The site will be published at:
   `https://<username>.github.io/<repository>/`
   - Landing page: `https://<username>.github.io/<repository>/index.html`
   - Privacy policy: `https://<username>.github.io/<repository>/privacy.html`

## Google Play
Use the **privacy policy URL** above in Play Console → *App content → Privacy policy*.
The privacy policy must also be reachable from **within the app**.

## Notes
- Keep the "Last updated" date in `privacy.html` current.
- Update both the Arabic and English sections when data practices change.
- `.nojekyll` disables Jekyll processing so all files are served as-is.
