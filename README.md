# NEXA MUSIC — local-first music player

A responsive, backend-free music library and player. Open `index.html` in a modern browser, or host this folder as a static site. No build step or account is needed.

## Working locally
- Import audio files from your device; audio blobs are stored in IndexedDB in this browser.
- Play, pause, seek, change volume, skip tracks, shuffle and repeat.
- Search imported track filenames/metadata, like tracks, and view liked/recent tracks.
- Create, edit, delete and fill playlists; playlist data, profile display name, bio, theme and listening history persist in localStorage.
- Export local library details as JSON (audio files themselves are not included).
- Mobile, desktop and tablet layouts; light/dark appearance.

## Important limits
This build intentionally has **no backend**. There is no server-side account/authentication, Google sign-in, cross-device sync, public catalog, streamed music, lyrics feed, artist/admin dashboard, real user social features, music/video hosting, recommendation service, subscription, payment processing or advertising. No sample streams or fake statistics are supplied. Local playback is for audio the listener imports and has rights to use. Browser storage capacity/retention varies; clearing browser data may erase the local library. File playback is limited by browser codec support.

## Files
- `index.html` — complete standalone application.
