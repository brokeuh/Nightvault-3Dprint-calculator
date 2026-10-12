# Nightvault Print Calculator

Installable web app (PWA) that works out what a 3D print costs and what to charge, for a Bambu Lab A1, A1 mini and Elegoo Saturn 16K. It also checks your year against the Belgian bijberoep threshold (€1,922.16 net profit, 2026) and the €25,000 VAT exemption limit.

Works offline after the first visit. Your inputs are saved on the phone.

## Put it online with GitHub Pages

1. Create a new public repository on GitHub, e.g. `Nightvault-3Dprint-calculator`.
2. Upload all files from this folder (keep the `icons` folder).
3. Go to **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute the app is live at https://brokeuh.github.io/Nightvault-3Dprint-calculator/.

## Install on Android

1. Open that address in **Chrome** on your phone.
2. Tap the **⋮** menu → **Install app** (or **Add to Home screen**).
3. It opens full-screen from your home screen, also without internet.

## Updating

Change the files, push to GitHub, and bump `CACHE` in `sw.js` (e.g. `print-calc-v2`). The app picks up the new version the next time it opens with internet.

Estimates only, not tax advice.
