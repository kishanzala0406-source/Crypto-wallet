# Crypto Wallet — mobile web app starter

## Publish free with GitHub Pages
1. Sign in to GitHub and create a **public** repository named `crypto-wallet`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. Open repository **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS URL in Safari.
6. In Safari, use Share → Add to Home Screen if you want an app-like icon.

## Current capabilities
- Selects BTC, ETH, USDT BEP20, USDT TRC20, USDT ERC20.
- Validates and saves public receiving addresses in browser local storage.
- Copy and remove address controls.
- PWA manifest and basic service worker shell.

## Important limitations
- This is an address-book prototype, not a wallet or exchange.
- No private keys, seed phrases, custody, transfers, QR generation, live balance, or blockchain monitoring.
- Addresses are stored in the browser on the current device. Clearing site data can erase them.
- Do not upload secrets or real wallet credentials. Test address formats carefully.
- A hosted app should be reviewed and security-tested before production use.
