EnjoyMuziki PWA Patch Notes

Changes added:
1. Install/Download App button remains available for PWA install.
2. Auto-next is enabled for local audio, local video, and YouTube iframe API when YouTube allows embedded playback.
3. Playing queue is kept separate from the list being viewed, so browsing another playlist does not change Next/Previous.
4. Local file upload now supports many audio and video files at once.
5. Local files are stored in the browser using IndexedDB.
6. Offline notice is shown when trying to play fixed YouTube content without internet.
7. Side menu includes Exit App.
8. Android/PWA-style double-back-to-exit prompt added.
9. Media Session API added for lock-screen/background controls where the browser supports it.

Important limitations:
- YouTube ads were not bypassed or skipped. The app uses standard YouTube embed behavior.
- A static web/PWA cannot scan the whole phone automatically. The user must select files/folders manually due to browser privacy rules.
- Background playback depends on the browser/OS. Local audio usually works better; YouTube embed background playback may be restricted by YouTube/mobile browser rules.

v0.5 Player Fit + Seek Patch
- Player section now fits the screen better and avoids unnecessary internal scrolling.
- Added live time counter for audio, video, and supported YouTube API playback.
- Added seek/progress bar and 10-second forward/back controls for audio and video.
- Added seek bar inside fullscreen mode.
- Changing Shuffle/Repeat mode no longer changes the currently playing song immediately.
- Updated service worker cache name so browsers load the new version.
