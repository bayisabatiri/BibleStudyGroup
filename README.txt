BIBLE STUDY GROUP — APK-READY WEBSITE FOLDER

Files:
- index.html: your app (existing Firebase configuration retained)
- manifest.json: installable PWA settings
- sw.js: app-shell offline cache; Bible chapters are cached by the app after successful reading
- icon.svg: app icon

HOW TO USE
1. Upload ALL files in this folder to the same folder/root of your GitHub Pages or Netlify site.
2. Keep the filenames exactly as they are. Do not upload index.html alone.
3. Open the deployed site using HTTPS, then reload it.
4. To install as an app on Android, open the site in Chrome and use the browser menu > Install app / Add to Home screen.
5. For a real APK, use a trusted PWA-to-APK wrapper (for example, PWABuilder) with the deployed HTTPS site URL.

IMPORTANT NOTES
- The original Firebase project configuration and app logic are retained; this package does not change Firebase security rules.
- Bible chapters can be read offline only after each chapter has been successfully opened online and cached. The full Bible is not bundled offline.
- Afaan Oromoo and Amharic chapter loading now uses the documented API versions `oromo` and `amhara`. The previous code used invalid WLD folder IDs (`oro`/`amh`), which caused both languages to fail. The API still needs an internet connection and its service must be online.
- This single HTML app still uses Firebase and online fonts/API sources, so first-time loading and shared data require internet.
