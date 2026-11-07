TAEKWONDO TERMINOLOGY — iPhone / Android Web App

This is a Progressive Web App (PWA), not an iOS .ipa. It uses the updated terms.json from your successful Android Studio project.

PUBLISH FOR FREE USING GITHUB PAGES
1. Sign in at https://github.com and create a new PUBLIC repository named taekwondo-terms.
2. Choose Add file > Upload files. Upload the CONTENTS of this folder (index.html, app.js, style.css, terms.json, sw.js, manifest.webmanifest, and both icons), not the ZIP or enclosing folder. Commit the files.
3. Open repository Settings > Pages. Under Build and deployment choose Deploy from a branch, branch main, folder /(root), then Save.
4. After deployment, open https://YOUR-USERNAME.github.io/taekwondo-terms/ in iPhone Safari.
5. Tap Share > Add to Home Screen > Add. Open the app from its Home Screen icon.

The app caches files after the first successful online visit for offline use. Test offline after loading once and adding to Home Screen. GitHub Pages requires the repository to be public on free plans; do not upload private information.

To update terms later: replace terms.json in the repository, and change the CACHE value in sw.js from tkd-terms-v1 to tkd-terms-v2 so installed devices fetch the new data.

The PWA retains the Android app quiz behavior: 11 belts, cumulative terms, four modes, accepted alternate Korean answers, and continuous randomized questions.
