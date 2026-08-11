# Your Portfolio Site

A single-page portfolio built with plain HTML/CSS (no build step needed) — ready to host on GitHub Pages.

## 1. Customize it

Open `index.html` in any text editor and replace the placeholder content:

- **Name & title** — top of `<nav>` and the `<h1>` in the hero section
- **About text & facts** — `#about` section
- **Skills table** — `#skills` section
- **Projects** — each `.project` block in `#projects` (title, description, tags, links)
- **Experience** — each `.log-entry` block in `#experience`
- **Contact links** — email, GitHub, LinkedIn, résumé link in `#contact`

The accent color, fonts, and layout are all controlled by the CSS variables at the top of the `<style>` block (`--accent`, `--paper`, `--ink`, etc.) if you want to adjust the palette.

## 2. Put it on GitHub Pages

**Option A — User/organization site** (`yourusername.github.io`):
1. Create a new repo named exactly `yourusername.github.io`
2. Upload `index.html` (and any other files) to the root of that repo
3. Go to Settings → Pages, and it should already be live at `https://yourusername.github.io`

**Option B — Project site** (any repo name):
1. Create or use any repo, e.g. `portfolio`
2. Upload `index.html` to the root
3. Go to Settings → Pages → under "Build and deployment," set Source to "Deploy from a branch," pick `main` and `/ (root)`, then Save
4. Your site will be live at `https://yourusername.github.io/portfolio`

It can take a minute or two for the first deploy to go live.

## 3. Adding a résumé PDF

The contact section links to `/resume.pdf`. Drop a `resume.pdf` file in the same folder as `index.html` (repo root) and that link will work automatically. If you don't have one yet, just remove that `<li>` from the contact links.

## 4. Optional: custom domain

If you own a domain, add a `CNAME` file (no extension) to the repo root containing just your domain, e.g. `www.yourname.com`, then point your DNS at GitHub Pages per [their docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
