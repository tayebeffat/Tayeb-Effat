# Portfolio Website

Static portfolio website prepared for GitHub Pages.

## Files

- `index.html` main page
- `styles.css` site styles
- `script.js` menu + reveal animations
- `ECoE CV-DR_Tayeb Brahimi.pdf` CV file used by "View CV" button

## Local preview

Open `index.html` directly in a browser.

## Customize before publish

- Update social links in `index.html`
- Replace placeholder experience/project/education content in `index.html`
- Set your email address in `index.html`

## Publish to GitHub Pages

After creating the GitHub repository:

```powershell
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin <YOUR_REPO_URL>
git push -u origin main
```

Then enable Pages in repo settings and choose:

- Branch: `main`
- Folder: `/ (root)`
