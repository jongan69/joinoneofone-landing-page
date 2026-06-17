# MDM Landing Page

This is a custom-styled, static MDM-branded landing page inspired by the structure of the previous site.

## Structure

- `index.html` — full homepage with updated MDM branding/theme
- `privacy-policy/index.html` — privacy policy page
- `terms-of-service/index.html` — terms of service page
- `assets/images/` — logo + favicon
- `funnel_mobile_assets/images/` — founder image, proof image, and student proof gallery
- `IMAGE_INVENTORY.md` — complete image requirements and replacement counts
- `.github/workflows/pages.yml` — GitHub Pages deploy workflow
- `.nojekyll` — keeps GitHub Pages from applying Jekyll processing

## Branding scope used now

- Primary brand name in page: **MDM**
- Cleaner color system + lighter, more minimal card treatment
- Same layout and flow preserved so you can keep your current conversion path intact
- Same embedded application widget and tracking hooks remain in place

## Image inventory (quick)

Use `IMAGE_INVENTORY.md` for the complete list and counts.

## Run locally

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/`.

## Push to GitHub Pages

A Pages workflow is included in `.github/workflows/pages.yml`.

If this repo is connected to your GitHub account, push to `main` and enable GitHub Pages.
