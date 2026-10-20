Bible Study Group — APK preparation folder

Contents
- index.html: your original uploaded website file, copied without changing its contents.
- manifest.json: installable PWA metadata.
- sw.js: service worker for caching the app shell.
- icons/: app icons.

How to use
1. Upload the CONTENTS of this folder to the same website folder/root (for example, the GitHub Pages or Netlify publish folder). Keep index.html, manifest.json, sw.js, and icons/ together.
2. Open the hosted site over HTTPS and test it in Chrome on Android.
3. To package as an Android APK, use a trusted PWA-to-APK/TWA builder or Android Studio with Bubblewrap, using the public HTTPS website URL.

Important
- This folder prepares the website for installation and APK packaging; it does not itself contain a compiled APK.
- The original HTML references Firebase and external Bible APIs. Online sign-in/data features and uncached Bible content still require internet. Service-worker caching alone does not make the entire app fully offline.
- For a working installable PWA, the site must be hosted over HTTPS. Test the hosted app before generating the APK.
