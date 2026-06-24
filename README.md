# Intuition Spatial Website

A static company landing page for Intuition Spatial, ready to publish on GitHub Pages.

## Files

- `index.html` — main website page
- `styles.css` — visual styling for the page
- `logo.svg` — company logo used in the header

## Deploy to GitHub Pages

1. Create a new GitHub repository for the site.
2. From this folder, initialize git if needed:
   ```bash
   git init
   git add .
   git commit -m "Initial Intuition Spatial website"
   ```
3. Add your GitHub repo remote and push:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
4. In GitHub, go to `Settings` > `Pages` and select the `main` branch and `/ (root)` folder.
5. Save the settings and wait a few moments for the site to deploy.

If the repo is named `<your-username>.github.io`, the site will publish at:

```
https://<your-username>.github.io/
```

Otherwise, it will publish at:

```
https://<your-username>.github.io/<repo-name>/
```
