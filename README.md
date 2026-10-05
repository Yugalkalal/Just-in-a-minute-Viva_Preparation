# JAM Viva Prep – 40 Topics

A zero-build static JAM viva practice app designed for GitHub + Vercel.

## Features
- 40 original JAM topics retained
- 1-minute preparation + 1-minute speaking timer
- Proper Fisher-Yates random topic deck
- Pause/resume and finish-early controls
- Key points for every topic
- Search titles + key points + keywords
- Persistent practice progress using localStorage
- 1–4 performance ratings
- Today's 10-topic goal
- Dark/light theme
- Reset progress
- PWA manifest + service worker for install/offline support
- Mobile-friendly layout
- No backend, npm install, or environment variables required

## Deploy on GitHub + Vercel

1. Put these files at the root of a GitHub repository.
2. Make sure the homepage is named `index.html`.
3. In Vercel, choose **Add New → Project** and import the GitHub repository.
4. Leave the build settings at their static-site defaults and deploy.
5. Every push to the connected production branch can trigger a new deployment.

## Local test

Open `index.html` directly for the main UI. For PWA/service-worker testing, use a local HTTP server rather than `file://`.

## Notes

Progress is stored locally in the visitor's browser. It is not synced between devices and no personal practice data is sent to a server.
