# Personal Website

Static site for GitHub Pages. Edit `index.html`, `styles.css`, and `script.js` to personalize content and visuals.

## Getting started
1. Update the placeholder text: name, bio, project blurbs, email/links.
2. Open `index.html` in your browser to preview locally.
3. Optional: run a simple server so relative links work nicely: `python3 -m http.server 8000`.

## Deploy on GitHub Pages
1. Push this repo to GitHub.
2. In Settings → Pages, set **Source** to the `main` branch (root).
3. After GitHub builds, your site is available at `https://<username>.github.io/<repo>/` or your custom domain if configured.

## Custom domain
- Add a `CNAME` file with your domain (e.g., `example.com`) and point DNS (CNAME or A/AAAA) to GitHub Pages per their docs.

## Notes
- The design uses Google Fonts (`Manrope`); swap or self-host if preferred.
- For privacy: update outbound links and remove any you don't use.
