# Glitch Stream

Real-time MJPEG webcam stream with compression level control, pixel sorting, and other glitch effects.

<video width="100%" autoplay loop muted playsinline>
  <source src="@media/demo-q.webm" type="video/webm">
  <source src="@media/demo.mp4" type="video/mp4">
  <img src="@media/demo.gif" alt="Demo">
</video>

## Browser Version (No Install)

Visit: **<a href="https://eisenbruch.github.io/vibe-coding-workshops/workshop-projects/2025-11-15-resistor/noah-eisenbruch-live-mjpeg-compression/index.html" target="_blank">Live Demo</a>**

## Server Version - Recommended (Local)

Has more accurate compression control.
Requires [Node.js](https://nodejs.org/) (v14 or higher)

### Setup

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo/live-mjpeg-compression
npm install
npm start
```

### View

Open http://localhost:3000 in your browser

## Controls

- **Enable Webcam** - Use your camera as the source image
- **Sliders** - Adjust glitch effects and JPEG compression in real-time
