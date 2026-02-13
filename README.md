# brockzacherl.com website

Multi-page personal developer website with:

- Home page promoting Brock as an iOS developer
- Portfolio section with three App Store apps
- Dedicated landing page for each app to drive App Store traffic

## Pages

- `/` -> `index.html`
- `/apps/fantasy-wrestling.html`
- `/apps/iwrestle.html`
- `/apps/weight-wingman.html`

## Run locally

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Why not Rails in this environment

Rails is a good fit for this project, but this machine currently has system Ruby `2.6.10` and old Bundler tooling that fails native gem setup for a standard Rails stack. The website is implemented with a no-dependency static stack so you can ship now. Once Ruby is upgraded (recommended: 3.2+ via `rbenv` or `asdf`), this can be migrated to Rails cleanly.
