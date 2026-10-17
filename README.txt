POCKET MONEY APP - FIRST WORKING VERSION

Files:
- index.html: app interface and functionality
- manifest.json: installable web app settings
- icon.svg: app icon
- sw.js: offline cache support when hosted over HTTPS/localhost

Features:
- Create account and login (local-device demo only)
- Record money received and purchases in INR
- Automatic balance, total received and total spent
- Date, optional reason and optional notes
- Edit and delete entries
- Search and filter activity
- Data saved in browser localStorage

IMPORTANT:
This is a local-first prototype, not a native APK. Account passwords are stored locally in browser storage and are NOT suitable for sensitive/real financial data. Data does not sync between devices. Clearing browser site data can erase the account and entries. A secure production version needs a backend and proper password hashing/authentication.

To install like an app:
1. Host these files on an HTTPS website (or run on a local development server).
2. Open the HTTPS URL in Chrome on Android.
3. Tap Chrome menu (three dots) > Add to Home screen / Install app.
4. Launch from the new home-screen icon.

Opening index.html as a local file will allow basic usage in many browsers, but PWA install/offline features generally require HTTPS or localhost.
