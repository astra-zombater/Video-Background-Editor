# 🎬 Virtual Studio Pro

> **Real-time AI Background Remover & Custom Background Studio — entirely in your browser[cite: 3]. Zero installations, zero heavy ML python setup, pure lightning-fast web magic.**
 
---

### 🚀 Built By
* **Astra Zomabter** 

---

### 💻 Live Demo

#1 : **https://videobgeditor.netlify.app**
#2 : **https://astra-zombater.github.io/Video-Background-Editor/**

---

### ✨ Features
* 🧠 **AI-Powered Selfie Segmentation:** Powered by Google MediaPipe right inside your browser via WebAssembly/CDNs.
* 🎥 **Dual-Mode Input Support:** Switch seamlessly between your **live webcam** or **upload any pre-recorded video file** from your device gallery.
* 🖼️ **Dynamic Background Swapping:** 
  * 🌁 Heavy Cinematic Blur
  * 🟢 Solid Green Screen Studio Mode
  * 📷 Custom Image Backgrounds
  * 🎞️ Looping Custom Video Backgrounds
* 🎛️ **Smart Precision Controls:** Built-in video playback controls (Play/Pause/Rewind) so you can stage your background before rolling.
* 🔴 **One-Click Record & Export:** Capture live sessions or processed clips instantly and download them directly as clean `.webm` video files.
* 📉 **Temporal Noise Smoothing:** Frame-blending buffers to eliminate jitter and give you stable, clean outlines.

---

### 🕹️ How to Run Locally
Because modern browsers enforce strict CORS policies on local machine files, you'll need a quick local web server to let MediaPipe load its neural network model binaries.

1. Clone or download this repository.
2. Open your terminal or command prompt inside the project folder.
3. Run a local server:
   * **Python 3:** `python -m http.server 8000`
   * **Node.js:** `npx serve`
   * **VS Code:** Just right-click `index.html` and hit **"Open with Live Server"**.
4. Open your browser and navigate to `http://localhost:8000` (or the port provided by your server). Allow camera permissions and start creating! 🚀
