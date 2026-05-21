# Zelei Personal Site

Static one-page website for quick launch on GitHub Pages.

## Local preview

Run from this folder:

```bash
python3 -m http.server 8080
```

Open: `http://localhost:8080`

## Deploy to GitHub Pages

1. Create a new repo on GitHub, e.g. `zelei-personal-site`.
2. Push this directory to `main`.
3. In GitHub repo settings, enable Pages:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Site URL becomes:
   - `https://<github-username>.github.io/zelei-personal-site/`

## Final replacements before sharing

- Replace `YOUR_EMAIL@illinois.edu` in `index.html`.
- Replace `YOUR_GITHUB_USERNAME` in `index.html`.
- Replace `YOUR_LINKEDIN_HANDLE` in `index.html`.
- Optional: add resume file at `assets/Zelei_Shao_Resume.pdf`.
- Optional: update `og:url` in `<head>` after deployment URL is known.

## Add profile photo

- Put your headshot at: `assets/profile.jpg`
- Recommended size: square image, at least `600x600`.

## Add one image per paper

1. Put each paper image into `assets/papers/`.
2. Use a stable file naming scheme, e.g.:
   - `assets/papers/mlsys2026.jpg`
   - `assets/papers/icml2026.jpg`
   - `assets/papers/neurips2025.jpg`
3. In `index.html`, update each publication `<li class="pub-item">` image `src`.
4. Recommended image ratio: around `3:2` (e.g. `900x600`) for clean cards.
