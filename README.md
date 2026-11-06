# Life on 11

Rugged, mobile-first Christian podcast and discipleship app.

## Publish with GitHub Pages
1. Add the app files from the launch package to the repository root: `index.html`, `manifest.webmanifest`, `service-worker.js`, and `icon.svg`.
2. In **Settings → Pages**, set the build source to **GitHub Actions**.
3. The included workflow will publish the site after files are committed to `main`.

The app currently uses local browser storage for personal progress and journal content. It does not yet have cloud accounts or cross-device sync.

Podcast episodes are read from the Life on 11 Transistor RSS feed.