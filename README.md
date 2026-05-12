# Sir Shotto App

Sir Shotto App is a mobile-friendly HTML music and video player designed for playing audio, video, YouTube links, local device files, and preview music from online search.

The app is built with pure HTML, CSS, JavaScript, Bootstrap, and Font Awesome.

## Developer

**Fidelis Paschal Shotto**  
Phone: **0629628637**

## Features

- Mobile-first responsive design
- Fixed search bar at the top
- Audio and video player
- YouTube video embedding
- Online music search using iTunes Preview API
- Local audio/video file import from device
- Playlist saving using browser localStorage
- Lyrics/details bottom sheet
- Rotating disc animation while music plays
- Audio waves animation
- Play, pause, next, and previous controls
- Play speed control
- Volume amplifier control
- Sound preset options:
  - Normal
  - Rock
  - Heavy Metal
  - Pop
  - Jazz
  - Classic
  - Bass Boost
  - Vocal
- Settings modal
- Add music manually using:
  - Audio file
  - Video file
  - Direct audio/video URL
  - YouTube link
- Fixed YouTube video list
- Clean mobile navigation

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Font Awesome
- iTunes Search API
- YouTube Embed

## Project Structure

```text
sir-shotto-app/
│
├── index.html
└── README.md

## Modified Version Notes

This version includes:

- PWA install/download support through `manifest.json` and `service-worker.js`.
- A Download / Install App button in the header and side menu.
- Fixed playback queue behavior: when a song starts from one list/playlist, Next/Previous continues from that same playing list even if the user opens another list.
- Immediate shuffle/repeat-one behavior: when music is already playing and the mode icon is changed, shuffle or repeat-one applies immediately without pressing Next again.
- Search/filter inside the currently opened list or playlist.
- YouTube iframe API support for detecting video end and moving to the next item automatically.
