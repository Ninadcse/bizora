# Bizora Business Premium — Demo

Includes a modern colourful access screen, business dashboard, local demo records, CSV export, and an Admin Panel. The demo access code is `147`.

## Publish to GitHub Pages
1. Download and extract the ZIP.
2. Open https://github.com/Ninadcse/bizora.
3. Replace the existing root `index.html` with this `index.html` and commit to `main`.
4. In Settings → Pages, select Deploy from a branch → `main` → `/(root)`.
5. Once published, open https://ninadcse.github.io/bizora/.

## Critical security note
The `147` gate is a demo-only client-side gate. Anyone can inspect the page source or browser storage and bypass it. It does **not** verify payment and cannot securely prevent unpaid people from accessing a public GitHub Pages site. To sell this as a paid app, implement server-side authentication, payment verification/webhooks, and server-side authorization with a backend and database. Do not use this demo to store sensitive financial or customer data.
