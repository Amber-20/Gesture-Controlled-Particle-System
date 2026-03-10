<div align="center">
  
# 🌌 Gesture Controlled Particle System

**An interactive WebGL particle simulation controlled by real-time hand gestures.**

[![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)](#)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-00B2A9?style=for-the-badge&logo=google&logoColor=white)](#)

</div>

> **Move your hand to rotate particle structures, pinch to expand particles, and make a fist to switch between dynamic 3D shapes.** This project combines computer vision and GPU-accelerated graphics to create a responsive visual experience directly in the browser.

---

## 🎥 Demo


🌐 **[Try the Live Demo Here](https://amber-20.github.io/Gesture-Controlled-Particle-System/)**

---

## ✨ Features

* **Real-time hand gesture interaction** via webcam detection
* **10,000+ GPU-accelerated particles** rendering smoothly
* **Dynamic 3D shape morphing** between multiple geometries
* **Smooth particle interpolation** for fluid transitions
* **Procedural particle noise motion** and animated color spectrums (HSL)
* **Responsive full-screen visualization** adaptable to any display

---

## 🖐️ Gesture Controls

| Gesture | Action |
| :--- | :--- |
| ✋ **Pinch** (thumb + index) | Expand or contract the particle structure |
| ✊ **Closed Fist** | Switch between available 3D shapes |
| 🖐️ **Move Hand** | Rotate the entire particle system |

---

## 🌠 Available Particle Shapes

The particle cloud dynamically morphs into multiple procedurally generated formations:
* Sphere
* Cosmic Flower
* Heart
* DNA Helix
* Torus
* Saturn Ring System

---

## 🧠 How It Works

### 3D Rendering
Particles are rendered using Three.js with `BufferGeometry`. This allows thousands of individual particles to be processed efficiently on the GPU rather than the CPU, maintaining high framerates.

### Hand Tracking

Hand gestures are detected using **MediaPipe Hands**, which maps and tracks 21 distinct hand landmarks from your live webcam feed. These landmarks dynamically update the rotation, scale, and shape-switching logic of the system.

### Particle Motion
Each individual particle includes targeted interpolation, random noise offsets, and continuous color cycling. When no hand is detected by the camera, the system defaults to a gentle "breathing" animation.

---

## ⚡ Installation

Clone the repository to your local machine:
```bash
git clone [https://github.com/Amber-20/Gesture-Controlled-Particle-System.git](https://github.com/Amber-20/Gesture-Controlled-Particle-System.git)

cd Gesture-Controlled-Particle-System

# Example using Python
python -m http.server

http://localhost:8000
```
---

## 📂 Project Structure
Gesture-Controlled-Particle-System
```│
├── index.html       # Main application logic, Three.js, and MediaPipe implementation

├── README.md        # Project documentation

├── LICENSE          # MIT License
```
---

## 🖥️ Requirements & Performance
Supported Browsers: Google Chrome, Microsoft Edge, Firefox, Safari (Must support WebGL).

Hardware: Webcam access must be enabled.

Optimization: Handles 10,000+ particles smoothly on most modern devices through Three.js BufferGeometry, GPU-accelerated rendering, and efficient animation loops.

---

## 🔮 Future Improvements
[ ] Multi-hand gesture support

[ ] Additional particle shapes

[ ] Audio-reactive particles

[ ] VR / AR interaction capabilities

[ ] Mobile gesture optimization

[ ] Particle trails and physics

[ ] Shader-based particle effects

---

## 📜 License & Author
Author: Amber

An interactive project exploring creative coding, computer vision, and real-time WebGL particle systems.

This project is licensed under the MIT License.
