# Emi's Hub — GitHub Pages / PWA

## Upload to GitHub
1. Create a new GitHub repository (for example: `emis-hub`).
2. Upload the CONTENTS of this folder to the repository root:
   - index.html
   - manifest.json
   - service-worker.js
   - icons/
3. In GitHub, open Settings > Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site and open the URL GitHub provides.

## Install on iPhone
1. Open the published Emi's Hub URL in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Confirm the name and tap Add.

## Moving your existing data
Before switching from the local HTML file:
1. Open your old Emi's Hub.
2. Export a backup if available.
3. In the hosted PWA, go to Tasks > Settings & Backup.
4. Choose Import Backup and select the JSON file.

Data is stored locally in your browser/device. GitHub hosts the app code, not your personal planner entries.

## Updating later
Replace the changed files in GitHub. The app data remains in browser storage. Export a backup before major updates or clearing Safari website data.
