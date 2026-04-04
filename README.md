# 🧵 NeonMesh

A real-time hand-tracking visual playground where your fingers generate glowing elastic connections in mid-air.

Built using MediaPipe Hands, NeonMesh transforms your hand movements into a dynamic neon web of animated strings and glowing nodes.

---

## ✨ Features

- 🔥 Real-time hand tracking (supports 2 hands)
- 🌈 Dynamic neon strings between finger joints
- ⚡ Elastic vibration based on movement speed
- 💡 Glowing, pulsing nodes with energy effects
- 🧠 Lightweight and runs directly in the browser
- 🎨 Smooth generative visuals (no lag, no setup)

---

## 🎮 How It Works

- The camera detects your hands and tracks key landmarks
- Selected points (fingers + joints) become **nodes**
- Every node connects to others forming a **living mesh**
- Moving your hands:
  - stretches the strings
  - creates vibration waves
  - shifts colors dynamically

---

## 🕹️ Controls

- ✋ Show your hands to the camera
- 🤏 Move fingers to stretch and animate strings
- 🌀 Faster movement = more vibration and glow
- 🖐️ Use two hands for more complex patterns

---

## 🛠️ Tech Stack

- HTML5 + CSS3
- JavaScript (Vanilla)
- Canvas API
- MediaPipe Hands (for hand tracking)
- WebRTC (camera input)

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/neonmesh.git
cd neonmesh
