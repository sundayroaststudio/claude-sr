# Sunday Roast site

Static HTML and CSS. No build step, no dependencies.

## Structure
- `index.html`: homepage (full copy)
- `services/` and `services/<name>/`: services index plus Brand Foundations, Brand Strategy, Marketing Roadmap, Sales Systems
- `projects/`, `about/`, `contact/`, `privacy-policy/`
- `404.html`, `.nojekyll`, `assets/style.css`

## Deploy on GitHub Pages
1. Push the contents of this folder to the root of a repository.
2. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. All links are relative, so it works at `username.github.io/repo/` and on a custom domain.
4. Custom domain: add it under Settings > Pages, then add a `CNAME` file containing the domain.

## Still to do
Subpages carry placeholders where the live copy was not available. Search for `Page copy to be added` and replace with the real text. No images are used. `404.html` links to `/`, so change that to the repo path if you host on a project URL rather than a custom domain.
