Hebrew Ulpan Flashcards PWA

FILES
- index.html
- manifest.webmanifest
- service-worker.js
- icons/

IMPORTANT
A PWA service worker requires the app to be served over HTTPS (or localhost).
Opening index.html directly from the iPhone Files app will not enable the PWA.

QUICK DEPLOY OPTIONS
1. Netlify Drop
   - Go to https://app.netlify.com/drop
   - Drag this entire folder onto the page
   - Netlify gives you an HTTPS web address

2. GitHub Pages
   - Upload the contents of this folder to a GitHub repository
   - Enable Pages in repository Settings

INSTALL ON IPHONE
1. Open the hosted HTTPS address in Safari
2. Tap Share
3. Tap Add to Home Screen
4. Open Hebrew Cards from the new Home Screen icon

OFFLINE
After the first successful load, the app shell is cached by the service worker.
The flashcards themselves are embedded in index.html, so the app can work offline.
