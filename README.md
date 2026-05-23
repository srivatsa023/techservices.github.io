# Techservice Static Site

A simple static webpage built with HTML, CSS, and JavaScript.

## GitHub Pages Deployment

1. Initialize git locally:

```bash
cd "c:\Users\sriva\OneDrive\Desktop\Web Development"
git init
git add .
git commit -m "Initial site commit"
```

2. Create a GitHub repository and connect it:

```bash
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

3. Enable GitHub Pages:

- Go to your repo Settings → Pages
- Under Source, choose `GitHub Actions` or `gh-pages`
- Save

The workflow under `.github/workflows/github-pages.yml` deploys the site automatically on every push to `main`.

## Notes

- Your homepage should be available at `https://<your-username>.github.io/<repo-name>/`.
- If you want a custom domain, add it in the Pages settings and configure DNS accordingly.
