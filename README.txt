# VibeWave MP3 Player

## Features
- Import and play local audio files from your device (files are not uploaded to a server).
- Play/pause, previous/next, seek, volume, shuffle, repeat, favorites and library search.
- Dark and light themes; theme preference is saved on this device.
- Online discovery buttons open YouTube and SoundCloud search pages.
- Installable PWA shell (GitHub Pages over HTTPS).

## GitHub Pages install
1. Extract this ZIP.
2. Open your GitHub repository.
3. Use Add file -> Upload files.
4. Upload `index.html`, `manifest.webmanifest`, `icon.svg`, and `sw.js` to the repository root. Do not upload the ZIP.
5. Commit to the branch configured for GitHub Pages (often `main`).
6. Open the published site over HTTPS and refresh. If an older cached version appears, close the tab and reopen; service worker updates can take a moment.

## Important limitations
- Local audio selections are not uploaded and the browser does not persist file access after a page reload. Re-select files when needed.
- Online buttons are links/searches to external services; they do not stream third-party music inside this app.
- Reliable background playback and lock-screen controls depend on the browser/device. For a fully native Android music player, a native app is needed.
- The PWA shell is cached for basic offline loading, but online links require internet.
