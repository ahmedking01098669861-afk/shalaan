# Deploy Instructions for *frenchciel*

This bundle is ready to deploy as a static site (HTML/CSS/JS).

## Local preview
```bash
python -m http.server 5500
# then open http://localhost:5500
```

## GitHub Pages
1. Create a new repository on GitHub (public or private).
2. Upload the contents of this folder (ensure `index.html` is present at the root).
3. Go to **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main**, Folder: **/**, Save.
4. Wait ~30–60 seconds for the site to build. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

> The `.nojekyll` file prevents Jekyll from interfering with your static assets.

## Netlify (Drag & Drop)
1. Visit https://app.netlify.com/drop
2. Drag the **contents** of this folder (or upload the `.zip` below).
3. You’ll get a public URL instantly.

## Vercel
1. Create a new project and import your GitHub repo (or drag this folder in the Vercel desktop app).
2. Framework preset: **Other** (static).
3. Deploy.

---
## Entry file
Detected entry file: `index.html`
