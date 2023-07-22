# GitHub Pages Deployment

```powershell
NODE_OPTIONS=--openssl-legacy-provider npm run build
git add dist -f
git commit -m "adding dist"
git subtree push --prefix dist origin gh-pages
```