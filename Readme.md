Neo-Geometry | 3D Cyberpunk Experience

A futuristic, interactive 3D landing page built entirely with Three.js and Tailwind CSS — featuring a procedurally generated “Data Core,” reactive lighting, and glitch-style UI animations. Everything runs inside a single HTML file, with zero build tools required.

🚀 Features
⚙️ Procedural 3D Assets

No external .gltf / .obj models.

Core artifact, debris rings, and particles are generated mathematically at runtime.

🖱 Interactive Controls

Central “Data Core” rotates based on mouse movement.

“Initialize Sequence” button triggers a smooth camera-zoom and color-shift animation.

💡 Reactive Lighting

Orbiting point lights create dynamic shadows and depth.

💻 Cyberpunk UI Effects

Custom glitch-text animations.

Glassmorphism panels built with Tailwind CSS.

📦 Zero Build Step

Runs directly in-browser using public CDNs.

No npm, webpack, or bundlers.

🛠️ Tech Stack

Three.js (r128) — WebGL rendering & 3D scene management

Tailwind CSS — Utility-first UI design

HTML5 + CSS3 — Structure, animations, and layout

📥 Installation & Usage

This project has no build pipeline. Just clone and open.

git clone https://github.com/ramanrishit448-RR/ThreeJS.git

Run the project

Open index.html directly in your browser OR

Use a local server (recommended for a smoother experience):

VS Code Live Server

python3 http.server

any lightweight dev server

Note: This file is CORS-safe, so it should work even without a server.

🎮 Controls
Action Result
Mouse Move Rotates the core artifact
Initialize Sequence Camera zoom + color transformation
Window Resize Canvas auto-resizes to fit viewport
🔧 Customization

All interactive parameters are inside the <script> section of index.html.

particleCount — Number of background stars
Default: 2000

isExploding Sequence — Modify color transitions on interaction

Geometry Tweaks — Adjust TorusGeometry, IcosahedronGeometry, or any procedural shape

Lighting — Change speed, intensity, or orbit radius of point lights

UI FX — Tweak glitch animation duration and CSS filters

This makes the project easy to fork and restyle.

📂 Project Structure
/ThreeJS
└── index.html # Single-file project (HTML + CSS + JS)

Everything — scene setup, shaders, controls, UI — is packed inside one file.

📝 License

This project is open-source under the MIT License.
You’re free to modify, distribute, or use it in your own work.
