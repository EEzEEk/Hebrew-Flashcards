# Hebrew Study Web App

A responsive, installable Hebrew flashcard study app.

## Run locally
Open `index.html` in a browser, or serve the folder with any static web server.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save. GitHub will provide the public URL.

## Install on a phone
Once hosted over HTTPS (GitHub Pages does this automatically):
- **Android/Chrome:** open the site → browser menu → **Add to Home screen** / **Install app**.
- **iPhone/Safari:** open the site → **Share** → **Add to Home Screen**.

The service worker caches the app for offline use after the first successful load.

## Responsive navigation
- Desktop/wide screens: study modes appear across the top.
- Phones/thin screens: study modes move into a slide-out vertical navigation drawer opened with the menu button.
