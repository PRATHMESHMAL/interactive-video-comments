# MyTube

A YouTube-style video player web application built with pure HTML, CSS, and JavaScript. It supports multiple videos, theme switching (Dark, Light, Neon), video selection, and a simple public comment system for each video.

---

## Features

- Responsive video player with controls
- Multiple sample videos with thumbnails and titles
- Dynamic video list for easy switching
- Theme switcher with Dark, Light, and Neon themes
- Public comment section per video, saved in memory during session
- Smooth UI transitions and animations
- Custom scrollbar styling
- Responsive layout suitable for desktop screens

---

## Demo

![Screenshot]()  
(Replace this with your own screenshot of the app)

---

## Usage

1. Open `index.html` in any modern web browser.
2. Use the buttons in the header to switch themes.
3. Click on any video in the video list to play it.
4. Add comments in the comment section; comments are saved per video during the current session.
5. The video player supports standard playback controls like play, pause, volume, and fullscreen.

---

## Project Structure

- `index.html` — Main HTML file containing markup, styles, and scripts.
- Uses Google Material Icons for UI icons.
- CSS styles use CSS variables for easy theming.
- JavaScript handles video switching, theme management, and comment functionality.

---

## Code Snippet Example

```html
<video id="videoPlayer" controls>
    <source id="videoSource" src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
