# ✦ AURA — Real-Time Audio Visualizer

AURA is a modern, interactive, browser-based **real-time audio visualizer** designed to transform music and audio into dynamic visual experiences.

It uses the **Web Audio API** for audio analysis and **HTML5 Canvas** for high-performance real-time rendering. The interface features a glassmorphism-inspired UI, animated gradients, responsive controls, multiple visualization modes, customizable themes, and audio-reactive effects.

> 🎵 Turn your audio into visuals.

---

## ✨ Features

### 🎧 Audio Input
- **System Audio** — visualize audio from your screen/system using browser screen sharing.
- **Microphone** — visualize live microphone input.
- **Demo Mode** — experience the visualizer without connecting an audio source.
- **Stop** — instantly stop the current visualization.

### 🌈 Visualization Modes

AURA includes multiple real-time visualization styles:

- ▐▐ **Bars**
- ∿ **Wave**
- ◎ **Circular**
- ✦ **Particles**
- ⫸ **Mirror**
- ◟ **Scope**
- ⌂ **Lissajous**
- ❋ **Spiral**

### 🎨 Visual Customization

Customize the visual experience using:

- Smoothing
- Bar count
- Gain
- Glow intensity
- Line width
- Bar gap
- Rotation
- Background trail/fade

### 🎭 Color Themes

Choose from multiple built-in palettes:

- Neon
- Fire
- Ice
- Aurora
- Mono
- Gold
- Cyber
- Vapor
- Matrix
- Sunset
- Cotton
- Void

### ⚡ Audio-Reactive Effects

Toggle different effects independently:

- Beat React
- Color Shift
- Afterglow
- Mirror X
- Frequency Grid
- Bass Shake
- Fill Mode
- Starburst

### 📊 Live Audio Statistics

AURA displays real-time information including:

- Volume
- Dominant frequency
- Bass
- Mid frequencies
- Treble
- BPM
- FPS
- Current visualization mode

The application calculates audio frequency data and updates the statistics continuously while the visualizer is running.

### 🖥️ Additional Controls

- Fullscreen mode
- Canvas snapshot/export
- Responsive layout
- Animated ambient background
- Glassmorphism UI
- Mobile-friendly responsive layout

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | UI, animations and responsive design |
| JavaScript | Application logic |
| Web Audio API | Audio analysis |
| HTML5 Canvas | Real-time visualization |
| CSS Gradients | Visual effects |
| Google Fonts | Typography |

The project is completely client-side and does not require a backend server or database.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/aura-visualizer.git
```

### 2. Open the project

```bash
cd aura-visualizer
```

### 3. Run the application

You can simply open:

```text
aura-visualizer.html
```

in a modern browser.

For the best experience, run it through a local web server.

For example, with VS Code, install **Live Server** and select:

```text
Open with Live Server
```

---

## 🎵 Using System Audio

Click:

```text
▶ system audio
```

Your browser will open a screen-sharing dialog.

Select the screen/window you want to share and make sure:

```text
Share audio
```

is enabled.

AURA then analyzes the shared audio stream using the Web Audio API.

---

## 🎤 Using Microphone

Click:

```text
🎤 mic
```

and allow microphone permission when the browser asks.

The microphone stream is analyzed in real time and converted into visual data.

---

## ✦ Demo Mode

Don't want to provide audio?

Click:

```text
✦ demo
```

AURA generates simulated frequency and waveform data so you can explore the visualizer without an external audio source.

---

## 📸 Snapshot

Click:

```text
📸 snap
```

to export the current canvas visualization as a PNG image.

The generated image is saved as:

```text
aura-snap.png
```

---

## 🎛️ Customization

AURA provides extensive controls for creating different visual styles.

### Visual Settings

Adjust:

- Smoothing
- Number of bars
- Gain
- Glow
- Line width
- Bar gap
- Rotation

### EQ Boost

Control the visual response of:

- Bass
- Low-mid
- Mid
- Treble
- High shelf

You can also change the FFT size to control audio frequency resolution.

---

## 📁 Project Structure

```text
aura-visualizer/
│
├── aura-visualizer.html
└── README.md
```

The current project is intentionally lightweight and contained in a single HTML file.

---

## 🌐 Live Demo

Once GitHub Pages is enabled, your project can be accessed at:

```text
https://YOUR-USERNAME.github.io/aura-visualizer/
```

---

## 🔒 Privacy

AURA is designed as a client-side application.

Audio visualization happens directly in the browser using the Web Audio API. No backend server or database is required.

Microphone and system-audio access require explicit browser permission.

---

## ⚠️ Browser Compatibility

For the best experience, use a modern browser such as:

- Google Chrome
- Microsoft Edge
- Firefox
- Safari

Some browser features, particularly system-audio capture, may behave differently depending on browser support and permission settings.

---

## 💡 Future Improvements

Possible future additions:

- 🎵 Drag-and-drop music file support
- 🎚️ Audio file playback
- 💾 Save/load visualization presets
- 🎨 Custom color editor
- 🎥 Record visualization as video
- 📱 Improved mobile audio support
- 🎼 Music metadata detection
- 🔊 More visualization algorithms
- 🖼️ Custom backgrounds
- ⌨️ Keyboard shortcuts

---

## 👨‍💻 Author

**Surya Manna**

Computer Science & Engineering Student

---

## ⭐ Support

If you like the project, consider giving the repository a ⭐ on GitHub.

---

### Built with HTML, CSS, JavaScript & Web Audio API

**AURA — See your sound.**
