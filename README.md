# Outreach Assistant: public site

Static site for the Outreach Assistant Chrome extension, served at https://outreach.mwk.dev.

- `index.html`: landing page (explainer, features, getting started, privacy policy at `#privacy`)
- `demo.html`: self-contained animated walkthrough, embedded in the landing page via iframe

Plain HTML, no framework and no build step.

## Run locally

    python3 -m http.server 8000

Then open http://localhost:8000.

## Deploy

Deploys to Cloudflare Pages from the `main` branch: framework preset none, no build command, output directory is the repository root.
