# Sweet D'oh Bakery — site preview

Static site: `index.html` + `img/`. No build step.

## Publish on GitHub Pages
1. Create a repo (e.g. `sweetdoh-site`) and push these files to the `main` branch.
2. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch `main` / folder `/ (root)` → Save.
3. The site appears at `https://<user>.github.io/sweetdoh-site/` within a minute or two.

## Before launch
- Fill the "Starting at $__" prices (search `$&thinsp;__`) and the dashed FAQ values (search `class="fill"`).
- Confirm the phone number (951) 477-0705 and the city (Murrieta vs. Menifee).
- Wire the quote form to email: the simplest route is Formspree — set `<form action="https://formspree.io/f/YOUR_ID" method="POST">` and delete the submit handler in the script at the bottom of the page.
- Package prices are the 2024 rates from the old site; update if they've changed.
