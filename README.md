# mhbg-A350
A pure html5 board game can be played on the airplane

## Deploy with GitHub Pages

This repository now includes an automatic GitHub Pages deployment workflow.

- Workflow file: `.github/workflows/deploy-pages.yml`
- Trigger: push to `main` and manual `workflow_dispatch`
- Deploy target: GitHub Pages (serving repository root as static site)

To enable it in the repository:

1. Go to **Settings → Pages**.
2. Set **Source** to **GitHub Actions**.
3. Push changes to `main` (or run the workflow manually) to publish updates.
