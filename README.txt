MY STUDY STARTER — iPhone setup

This is a small, installable web app (PWA). It stores progress locally on the device/browser and does not require an account.

IMPORTANT: To install it as an app icon on iPhone, it must be hosted at an HTTPS address. Opening index.html directly from Files is useful for a preview, but does not provide the full Add to Home Screen experience.

Files:
- index.html: the app
- manifest.webmanifest: install settings
- sw.js: offline cache

Quick publishing option:
1. Create a GitHub account (if needed) and a new public repository named study-starter.
2. Upload index.html, manifest.webmanifest, and sw.js to the repository's main/root folder.
3. In the repository, open Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch, branch main, folder /(root), then Save.
5. Wait for the published HTTPS address shown on the Pages screen.
6. Open that address in Safari on the iPhone.
7. Tap Share → Add to Home Screen → Add.

The app saves points and checklist progress in Safari's local storage. Keep using the same iPhone and do not clear Safari website data, or that local progress may be erased.
