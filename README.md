# Memoshot — Photobooth Studio & Events Manager

A first-version, browser-based Progressive Web App for Android and desktop.

## Included
- Camera capture with filter options
- Classic 4-photo 2×6 strip, 2×2 collage, and single-image print layout
- Download and browser printing
- Local event gallery and image import
- Booking records, balances, customer records, settings
- JSON backup/restore and CSV booking export
- Local browser storage and service-worker shell caching for offline launch

## Important limitations
- Camera access requires HTTPS or localhost and permission.
- Records are stored locally in the current browser/device; they do not sync between devices.
- QR-based cross-device gallery sharing is not included yet; that requires online image hosting and shareable URLs.
- Beauty effects are not advanced AI retouching; current effects are simple CSS/canvas filters.
- Printing depends on the printer and browser's print dialog.
- Local storage is not encrypted and may be cleared by browser/device cleanup. Export backups regularly.

## Run locally
Serve this folder from localhost (not by opening index.html as a file), or deploy it to a static HTTPS host such as GitHub Pages.

## Android install
1. Deploy the files to GitHub Pages.
2. Open the published HTTPS URL in Chrome on Android.
3. Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.
4. Allow camera permission when using the studio.
5. Open Settings & Backup and download a backup regularly.

## Desktop install
Open the HTTPS URL in Chrome or Edge and use the install icon in the address bar, or browser menu → Install Memoshot.
