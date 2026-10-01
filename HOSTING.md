# Pocket Ledger: put it online once, use it offline forever

Files: index.html, manifest.json, sw.js, icon-192.png, icon-512.png (keep them together in one folder).
Hosting must be HTTPS (GitHub Pages and Netlify both are).

## Option A: GitHub Pages
1. Create a free GitHub account and a new repository (e.g. "ledger").
2. Upload all five files to the repository (Add file > Upload files).
3. Settings > Pages > deploy from the main branch, root folder. Wait a minute.
4. Open the https://<your-name>.github.io/ledger/ link in Chrome on your phone.

## Option B: Netlify
1. Go to app.netlify.com/drop and drag this folder onto the page.
2. Open the generated https link in Chrome on your phone.

## Install on the phone
1. Open the link once with internet and let it finish loading.
2. Chrome menu (three dots) > Install app (or Add to Home screen).
3. Turn on airplane mode and open it from the home screen to confirm it works offline.
4. Go to Accounts > Security and set your PIN.

## Moving your data from the earlier version
In the old version: Accounts > Copy backup, and save the text privately.
In the new app: Accounts > paste into the backup box > Restore.
(Browser storage is separate for each web address, so data does not carry over by itself.)

## Notes
- The hosting site only serves the code. Your entries never leave your phone.
- The PIN is a lock screen, not encryption. Keep your phone screen lock on.
- Forgot PIN erases the data on that device; restore from your backup.
- Clearing Chrome site data deletes your entries. Copy a backup regularly.
