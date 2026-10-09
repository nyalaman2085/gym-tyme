# GYM TYME — Gym Equipment Landing Page

Responsive static landing page concept with desktop and mobile layouts, product imagery, and a client-side equipment request preview.

## Demo

- Desktop: https://nyalaman2085.github.io/gym-tyme/
- Mobile layout: https://nyalaman2085.github.io/gym-tyme/mobile.html

These URLs depend on GitHub Pages being enabled and the deployment workflow succeeding. Check the Actions tab for current deployment status.

## Features

- Separate desktop and mobile-focused pages
- Responsive equipment cards and product imagery
- Required name/email fields and equipment selection
- Client-side request preview with accessible status feedback

**Scope limitation:** the form is a frontend demo. It does not submit a real order, send email, reserve stock, or store personal information. Do not enter sensitive information.

## Run locally

From the repository root:

\`\`\`bash
python3 -m http.server 8000
\`\`\`

Open http://localhost:8000/ and http://localhost:8000/mobile.html.

## Project structure

- \`index.html\` — main landing page
- \`mobile.html\` — mobile-focused page
- \`css/style.css\` — desktop styling
- \`css/mobile.css\` — mobile styling
- \`images/\` — logo assets
- \`.github/workflows/deploy-pages.yml\` — GitHub Pages deployment

## Tech stack

HTML5 · CSS · JavaScript · GitHub Pages

## Next engineering step

A genuine booking flow would need a backend API, server-side validation, privacy notice, secure storage, and a confirmation mechanism. The current demo intentionally does not pretend to provide those services.
