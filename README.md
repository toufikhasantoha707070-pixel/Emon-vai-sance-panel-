# APK Download Gate

## Important
This package is a GitHub Pages-ready frontend demo.

It currently:
- links to the supplied Facebook and TikTok profiles
- checks the supplied password client-side
- collects a Gmail address only for the demo UI
- provides the APK download after the demo gate

### Production approval
Do NOT collect Gmail passwords. For real approval, connect this page to a backend/database and Google OAuth or an admin approval workflow.

GitHub Pages can host the frontend, but it cannot securely store the approval state or send approval emails by itself.

## GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and the `assets` folder.
3. Enable GitHub Pages from Settings → Pages.
