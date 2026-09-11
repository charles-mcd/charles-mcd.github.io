# Personal website

Built with [Quarto](https://quarto.org), published on GitHub Pages.

## First-time setup

1. Install Quarto: https://quarto.org/docs/get-started/
2. Replace placeholders: search the folder for `YOUR-` and `TODO`.
3. Add `profile.jpg` (headshot) to the root folder.
4. Preview locally: `quarto preview`
5. Create a public GitHub repo named exactly `YOUR-GITHUB-USERNAME.github.io`,
   push this folder to it.
6. Publish: `quarto publish gh-pages`
   (builds the site and pushes it to a `gh-pages` branch).
7. On GitHub: Settings → Pages → Source: "Deploy from a branch",
   branch `gh-pages`, folder `/ (root)`.

## Updating

Edit the `.qmd` files, then run `quarto publish gh-pages` again.

## Custom domain (optional, later)

Add the domain in Settings → Pages → Custom domain, create the DNS records
your registrar asks for, and update `site-url` in `_quarto.yml`.
