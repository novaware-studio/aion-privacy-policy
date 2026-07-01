# Vigil Privacy Policy — GitHub Pages

This directory contains the static privacy policy page for Vigil.

## How to deploy

1. **Create a new GitHub repo** (e.g. `Novaware/vigil-privacy-policy` or use
   a `privacy` subdirectory on an existing `novawarestudio.com` Pages repo).

2. **Push the contents of this directory** to the repo's default branch:
   ```bash
   cd privacy-policy
   git init
   git add .
   git commit -m "Privacy policy page"
   git remote add origin git@github.com:Novaware/vigil-privacy-policy.git
   git push -u origin main
   ```

3. **Enable GitHub Pages** in the repo's Settings → Pages:
   - Source: "Deploy from a branch"
   - Branch: `main`, folder: `/ (root)`

4. The page will be available at:
   - `https://novaware.github.io/vigil-privacy-policy/`
   - Or at a custom domain if configured (e.g. `https://novawarestudio.com/vigil/privacy`)

5. **Enter this URL** in the Google Play Console under:
   - Store listing → Privacy policy URL
   - Data safety → Privacy policy URL

## Updating

Edit `index.html` directly. Update the "Last updated" date in the page
whenever you make changes. Push and GitHub Pages will redeploy automatically.
