🌌 Neural Dust v3

Neural Dust v3 is an interactive WebGL particle system that uses real-time hand tracking to manipulate dynamic 3D particle formations. Using your webcam, you can control particle behavior, rotate the system, expand structures, and switch between complex shapes with simple hand gestures.

The project combines 3D graphics with AI-powered hand tracking to create a responsive visual experience directly in the browser.

Built using:

Three.js

MediaPipe Hands

WebGL

JavaScript

HTML / CSS

✨ Features
🖐 Gesture Controls

The particle system reacts to your hand movements in real time.

Gesture	Action
✋ Pinch (thumb + index finger)	Expand or contract particle formations
✊ Closed fist	Switch between particle shapes
Move hand	Rotate the particle system
🌠 Particle Shapes

Neural Dust dynamically morphs between several 3D structures:

Sphere

Cosmic Flower

Heart

DNA Helix

Torus

Saturn Ring System

Each structure contains 10,000 particles rendered with additive blending and animated noise for organic motion.

🧠 How It Works
3D Particle Engine

The system uses Three.js to render a particle cloud using BufferGeometry.

Particles smoothly interpolate between target positions to morph between shapes.

Hand Tracking

Hand gestures are detected using MediaPipe Hands, which tracks 21 landmarks per hand from the webcam feed.

These landmarks control:

Rotation

Scaling

Shape switching

Motion Effects

Particles include:

Per-particle random offsets

Dynamic color cycling (HSL spectrum)

Noise-based motion

Breathing effects when no hand is detected

📷 Interface

The application includes:

Fullscreen particle visualization

Live webcam preview

Gesture instructions

Real-time system status

Current shape indicator

🚀 Installation

Clone the repository:

git clone https://github.com/amber-20/Particle-Despersion.git

Particle-Despersion

Run using any local server:

Then open:

http://localhost:8000

⚠️ Webcam access requires running the project through localhost or HTTPS.

📂 Project Structure
neural-dust-v3
│
├── index.html        # Main application
├── README.md         # Project documentation

All logic is currently contained in a single HTML file for simplicity.

🖥 Requirements

Modern browser with WebGL support:

Chrome

Edge

Firefox

Safari

Webcam access must be enabled.

⚙️ Performance

Optimized for smooth performance:

10,000 particles

GPU accelerated rendering

BufferGeometry optimization

Efficient animation loops

Runs best on:

Desktop GPUs

Modern laptops

High performance mobile devices

📸 Demo Ideas

You can use this project for:

Creative coding portfolios

Interactive installations

WebGL experiments

Gesture-based UI research

Visual art projects

🔮 Possible Future Improvements

Multiple hand support

Gesture recognition for more commands

Custom particle shapes

Audio reactive particles

VR / AR support

Particle trails

Mobile gesture optimization

📜 License

MIT License

Feel free to use, modify, and distribute this project.

👨‍💻 Author

Created as a creative coding experiment combining AI vision and WebGL particles.
