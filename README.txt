BIBLE STUDY GROUP — APK PREPARATION FOLDER

Included:
- index.html: original website with Bible verse loading fixed for Afaan Oromoo and Amharic.
- manifest.json and sw.js: PWA shell for hosting/installing.
- icons/: app icons.

Bible verses:
- English uses bible-api.com (KJV).
- Afaan Oromoo uses the Oromo endpoint of bible-api-kappa.vercel.app.
- Amharic uses the Amharic endpoint of bible-api-kappa.vercel.app.
These two non-English endpoints need internet. Chapters that have been successfully opened are saved in the app's local IndexedDB cache, but the entire Bible is not preloaded for offline use.

To test:
1. Upload the contents of this folder to your website host (keep the folder structure).
2. Open the site while connected to the internet.
3. Sign in, select Afaan Oromoo or አማርኛ, open Reading, choose a book and chapter, and press Read.
4. If the API provider is temporarily unavailable, try again later.

This is not a compiled APK. Use a PWA-to-APK tool or Android Studio wrapper after hosting the website over HTTPS.
