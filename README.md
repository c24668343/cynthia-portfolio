# Cynthia Pan — Portfolio

Static site for GitHub Pages. No build step.

```
index.html          the whole site (HTML + CSS + a small scroll-spy script)
assets/portrait.jpg hero photo
files/              résumé and project reports (student IDs removed)
.nojekyll           tells GitHub Pages to serve files as-is
```

## Deploy

1. Create a public repository named `<your-github-username>.github.io`.
2. Upload everything in this folder to the repository root (keep `index.html` at the top level).
3. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
4. The site goes live at `https://<your-github-username>.github.io/` within a minute or two.

## Before you publish

- Put your résumé PDF at `files/resume.pdf` (exported from Canva).
- To add GitHub / LinkedIn links, edit the contact row in the hero section of `index.html`.
