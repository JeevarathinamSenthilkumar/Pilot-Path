# Pilot Path — iPhone navigation fixed + shared files

Download ZIP, extract, open index.html on Windows, or upload the unzipped root to GitHub Pages.

## Fixes
- All chapters back button is below the iPhone status bar.
- Removed repeated chapter header logo; logo is retained on landing page and Home Screen.
- All chapters share one `shared/chapter.css` and one `shared/chapter-mobile.css`.
- Removed duplicate chapter icons, service workers, manifests, redundant JSON copies (lesson data remain in JS), and deployment-unnecessary documentation.
- The root service worker updates to version 4; visited chapters and their assets are cached for subsequent offline use after first successful load.
- Existing localStorage progress keys are unchanged. Upload to the SAME GitHub Pages repo URL to retain progress.

Note: First-time offline use of individual chapters requires opening those chapters online first; this slim version does not pre-download every chapter automatically.
