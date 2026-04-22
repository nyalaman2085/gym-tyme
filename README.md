# GYM TYME

Static landing page for a gym brand with separate desktop and mobile entry pages.

## Live Site

Once GitHub Pages is enabled and the repository is pushed, the site will be available at:

`https://nyalaman2085.github.io/gym-tyme/`

Mobile page:

`https://nyalaman2085.github.io/gym-tyme/mobile.html`

## Project Structure

- `index.html` - main landing page
- `mobile.html` - mobile-focused landing page
- `css/style.css` - desktop styles
- `css/mobile.css` - mobile styles
- `images/` - logo assets
- `.github/workflows/deploy-pages.yml` - GitHub Pages deployment workflow

## Run Locally

This is a plain static site, so you can open it directly in a browser:

```bash
open index.html
open mobile.html
```

## Deploy With GitHub Pages

This repository includes a GitHub Actions workflow that deploys the site from the `main` branch.

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to `Settings` -> `Pages`.
4. Under `Build and deployment`, set `Source` to `GitHub Actions`.
5. Push to `main` or run the `Deploy GitHub Pages` workflow manually from the `Actions` tab.

After the workflow finishes, GitHub Pages will publish the site automatically.

## Notes

- `index.html` is the default homepage.
- `mobile.html` is deployed as a second public route.
- All internal asset links are relative, so the site works on GitHub Pages without code changes.
