# ExamTrack PWA

## What is included
- Installable Progressive Web App (PWA)
- Daily study checklist and progress
- 4-hour suggested daily study routine
- Weekly schedule
- Exam target list
- Mock-test score history and study-hour logging
- Local browser storage and JSON backup/restore
- Offline app shell after the first successful load

## Important
The app must be hosted on HTTPS for PWA installation and offline service-worker support. Opening `index.html` directly from your phone's file manager is useful for a quick preview, but it will not enable full PWA installation.

## Publish using GitHub Pages from an Android phone
1. Extract this ZIP on your phone.
2. In Chrome, open https://github.com and sign in or create an account.
3. Create a **public** repository named `examtrack`.
4. Open the repository, choose **Add file → Upload files**.
5. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and the `icons` folder with both PNG files. Keep the folder structure exactly as provided.
6. Commit the files to the `main` branch.
7. Open repository **Settings → Pages**.
8. Under **Build and deployment**, choose **Deploy from a branch**; select branch `main` and folder `/ (root)`, then Save.
9. Wait for GitHub Pages to publish. Your app address will be `https://YOUR-USERNAME.github.io/examtrack/`.
10. Open that address in Chrome. Use Chrome menu (⋮) → **Install app** or **Add to Home screen**.

## Your data
Study data is saved in the browser storage on the device. Use **More → Export my data** regularly to create a backup. Clearing Chrome site data or switching browsers/devices can remove or separate local data. The app does not sync to a server.
