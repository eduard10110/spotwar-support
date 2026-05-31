# SpotWar — GitHub Pages (Support & Privacy)

Static pages for App Store Connect.

## Live URLs (after deploy)

| Purpose | URL |
|--------|-----|
| **Support URL** | https://eduard5551.github.io/spotwar-support/ |
| **Privacy Policy URL** | https://eduard5551.github.io/spotwar-support/privacy.html |

## Deploy to GitHub Pages

1. Create a **public** repo on GitHub named exactly: `spotwar-support`
   - https://github.com/new → name: `spotwar-support` → Public → Create

2. Push this folder to that repo:

```bash
cd spotwar-support
git init
git add index.html privacy.html README.md
git commit -m "Add SpotWar support and privacy pages"
git branch -M main
git remote add origin https://github.com/eduard5551/spotwar-support.git
git push -u origin main
```

3. Enable Pages: repo **Settings → Pages → Branch: main → / (root) → Save**

4. Wait 1–3 minutes, then open the Support URL in a browser to verify.

## App Store Connect

Paste the Support and Privacy URLs from the table above into your app listing.
