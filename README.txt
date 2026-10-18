BIBLE STUDY GROUP — Afaan Oromoo + Amharic Bible reader update

Upload the three files in this folder to the SAME folder in your existing GitHub Pages repository, replacing index.html, manifest.json and sw.js. Keep the existing app folder/path.

The Bible reader now uses the selected language: English (KJV), Afaan Oromoo (Oromo), or Amharic (Amhara). Once a chapter successfully loads online, that chapter is saved in the browser's IndexedDB and can be read offline on that same device/browser. Chapters are cached as the user reads them; this does not pre-download the entire Bible.

Important: Oromo/Amharic depend on the third-party Bible API documented at https://github.com/abdiu34567/Bible-Api. If that service is unavailable, first-time chapter downloads will fail; previously cached chapters remain available offline. This package was code-reviewed but the live API could not be reached from the build environment, so test Genesis 1 in all three languages after publishing.
