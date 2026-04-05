# 🧵 NeonMesh

A real-time hand-tracking visual playground where your fingers generate glowing neon connections in mid-air.

Built using MediaPipe Hands, NeonMesh transforms your hand movements into a dynamic mesh of animated strings and glowing nodes — runs entirely in the browser, no install needed.

---

## ✨ Features

- 🔥 Real-time hand tracking (supports up to 2 hands)
- 🌈 Neon strings that connect only your raised fingers
- ⚡ Elastic vibration based on movement speed
- 💡 Glowing pulsing nodes with spark rays
- 🖥️ Live HUD showing position, velocity, spread & frame data
- 🎨 Smooth generative visuals with zero setup

---

## 🎮 How It Works

- Camera detects your hands and tracks key landmarks
- Only **raised / extended fingers** become active nodes
- Every active node connects to others forming a **living mesh**
- Moving your hands stretches strings, creates vibration waves and shifts colors dynamically
- Point **1 finger** → 1 node, no strings
- Point **2 fingers** → 1 string
- Point **more fingers** → exponentially more strings

---

## 🕹️ Controls

- ✋ Show your hands to the camera
- ☝️ Raise fingers to activate nodes and create strings
- 🤏 Move fingers to stretch and vibrate the strings
- 🌀 Faster movement = more vibration and glow
- 🖐️ Use two hands for more complex neon patterns

---

## 🖥️ Live HUD

A real-time data panel in the top-left corner displays:

| Field | Description |
|-------|-------------|
| HANDS | Number of hands detected |
| FINGERS | Active (raised) finger count |
| STRINGS | Number of live connections |
| POS X / Y | Centroid position of all nodes |
| VELOCITY | Movement speed in px/frame |
| SPREAD | Max distance between nodes |
| FRAME | Total frames rendered |
| STATUS | IDLE / TRACKING / ACTIVE |

---

## 🛠️ Tech Stack

- HTML5 + CSS3
- JavaScript (Vanilla)
- Canvas API
- MediaPipe Hands
- WebRTC (camera input)

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/neonmesh.git
cd neonmesh
```

### 2. Open in browser
Just open `index.html` in any modern browser — no server needed.
```bash
open index.html
```

### 3. Allow camera access
When prompted, allow the browser to access your camera. Works best in Chrome or Edge.

---

## 📁 Project Structure
```
neonmesh/
└── index.html     # entire app — single file, no dependencies to install
└── README.md      # project documentation
```

---

## 📌 Notes

- Works best in **Chrome** or **Edge**
- Requires a working **webcam**
- Best used in a **well-lit environment** for accurate hand detection
- No data is sent anywhere — everything runs locally in your browser

---

## 📄 License

MIT — free to use, modify and share.
