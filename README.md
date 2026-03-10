🌌 Gesture Controlled Particle System








An interactive WebGL particle simulation that can be controlled using real-time hand gestures through your webcam.

Move your hand to rotate particle structures, pinch to expand particles, and make a fist to switch between dynamic 3D shapes.

The project combines computer vision and GPU-accelerated graphics to create a responsive visual experience directly in the browser.

Built using:

Three.js

MediaPipe Hands

WebGL

JavaScript

HTML / CSS

🎥 Demo

(Add a screen recording GIF here later)

demo.gif

Example once added:

![Demo](demo.gif)
✨ Features

Real-time hand gesture interaction

10,000+ GPU-accelerated particles

Dynamic 3D shape morphing

Smooth particle interpolation

Procedural particle noise motion

Animated color spectrum (HSL)

Webcam gesture detection

Responsive full-screen visualization

🖐 Gesture Controls
Gesture	Action
✋ Pinch (thumb + index finger)	Expand / contract particle structure
✊ Closed fist	Switch between shapes
Move hand	Rotate particle system
🌠 Available Particle Shapes

The particle cloud dynamically morphs into multiple formations:

Sphere

Cosmic Flower

Heart

DNA Helix

Torus

Saturn Ring System

Each shape is procedurally generated and animated in real time.

🧠 How It Works
3D Rendering

Particles are rendered using Three.js with BufferGeometry, allowing thousands of particles to be processed efficiently on the GPU.

Hand Tracking

Hand gestures are detected using MediaPipe Hands, which tracks 21 hand landmarks from the webcam feed.

These landmarks are used to control:

Particle rotation

Particle scaling

Shape switching

Particle Motion

Each particle includes:

Target interpolation

Random noise offsets

Color cycling

Breathing animation when no hand is detected

⚡ Installation

Clone the repository:

git clone https://github.com/Amber-20/Gesture-Controlled-Particle-System.git

Navigate into the folder:

cd Gesture-Controlled-Particle-System

Run a local server:

Example using Python:

python -m http.server

Open the project in your browser:

http://localhost:8000

⚠️ Webcam access requires localhost or HTTPS.

🌐 Live Demo

Once GitHub Pages is enabled, the project can run directly in the browser.

https://amber-20.github.io/Gesture-Controlled-Particle-System/
📂 Project Structure
Gesture-Controlled-Particle-System
│
├── index.html
├── README.md
├── LICENSE
└── demo.gif (optional)

All main logic currently runs inside index.html for simplicity.

🖥 Requirements

A modern browser with WebGL support:

Google Chrome

Microsoft Edge

Firefox

Safari

Webcam access must be enabled.

🚀 Performance

The particle system is optimized for performance using:

Three.js BufferGeometry

GPU accelerated rendering

Efficient animation loops

The system handles 10,000+ particles smoothly on most modern devices.

🔮 Future Improvements

Possible upgrades:

Multi-hand gesture support

Additional particle shapes

Audio-reactive particles

VR / AR interaction

Mobile gesture optimization

Particle trails and physics

Shader-based particle effects

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Amber

Interactive project exploring creative coding, computer vision, and real-time WebGL particle systems.
