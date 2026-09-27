# JMD Billing — installable app wrapper

A tiny PWA shell that full-screens the JMD Billing Apps Script web app so it can be installed
like an app (Add to Home Screen / Install). The billing app's code lives in the private
`jmd-billing` repo; this repo contains **no app link and no data**.

On first launch the page asks for the app's `/exec` link and stores it in that device's
`localStorage`. Use the small "change link" button (bottom-right) to reset it.

Install: open the GitHub Pages URL, then **Install app** (Chrome/Edge) or
**Share → Add to Home Screen** (iPhone).

Files: `index.html` (wrapper), `manifest.webmanifest`, `sw.js` (caches the shell only), `icons/`.
