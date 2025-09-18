# Nuno Loureiro — GitHub Pages

This is a minimalist personal site inspired by [diffuse.one](https://diffuse.one/).

## Local preview
Just open `index.html` in a browser, or use a tiny static server:
```bash
python3 -m http.server 8080
```

## Deploy to GitHub Pages (user/organization site)
1. Create a repo named **`<your-username>.github.io`**.
2. Push these files to the default branch (usually `main`).
3. Pages will deploy automatically at `https://<your-username>.github.io/`.

## Deploy to GitHub Pages (project site)
1. Create a repo with any name (e.g., `portfolio`).
2. Push these files to the default branch.
3. In **Settings → Pages**, set **Build and deployment** to **Deploy from a branch**, and select **Branch: `main`, Folder: `/ (root)`**.
4. Your site will be at `https://<your-username>.github.io/<repo>/`.

### Custom domain (optional)
- Add your domain to **Settings → Pages** under **Custom domain**.
- Replace the `CNAME` file with your real domain (e.g., `nuno.example`).
- Point your DNS to GitHub Pages (A/AAAA and CNAME records per GitHub docs).

> `.nojekyll` is included to skip Jekyll processing (useful when serving files/folders starting with `_`).

