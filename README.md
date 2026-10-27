# Pathwise School

A separate GitHub Pages copy of Pathwise, kept separate from the main Vercel project.

## Deploy
The GitHub Actions workflow publishes the `public/` folder to GitHub Pages on pushes to `main`.

Expected URL: https://aaravghub.github.io/pathwise-git/

## Important
GitHub Pages only hosts static files. The Genesis login and live grade/schedule sync use `/api/login` and `/api/sync`, which require a compatible backend. Do not enter real Genesis credentials on this static copy until that backend is configured and verified.
