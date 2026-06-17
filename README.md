# MDM Website Replica

This repository is a static replica of the public landing page at
`https://joinoneofone.com`, including all inline HTML/CSS and page sections
from the public site.

## Structure

- `index.html` — full homepage replica
- `privacy-policy/index.html` — privacy policy page
- `terms-of-service/index.html` — terms of service page
- `assets/images/` — logo + favicon
- `funnel_mobile_assets/images/` — all testimonial/screenshot assets used on the page

## Run locally

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Publish to GitHub Pages

Create a new GitHub repository and push these files (or run inside an existing repo). If your repo is hosted at `https://github.com/<you>/<repo>`, GitHub Pages can serve from either the `main` branch root or from a Pages workflow.

A Pages workflow is included in `.github/workflows/pages.yml`.

