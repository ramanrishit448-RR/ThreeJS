Neo-Geometry | 3D Cyberpunk Experience

A futuristic, interactive 3D landing page built with Three.js and Tailwind CSS. This project features a procedurally generated "Data Core" artifact, reactive lighting, and glitch UI effects, all contained within a single HTML file for easy deployment.

🚀 Features

Procedural 3D Assets: No external .gltf or .obj files required. The central core, debris rings, and particle systems are generated mathematically at runtime.

Interactive Camera & Controls: \* The core rotates based on mouse position.

"Initialize Sequence" button triggers a smooth camera zoom and color shift animation.

Reactive Lighting: Dynamic point lights orbit the center to create depth and shadow.

Cyberpunk UI: Custom CSS animations for glitch text effects and glassmorphism panels.

Zero Build Step: Runs directly in the browser using CDNs.

🛠️ Technologies Used

Three.js (r128): For WebGL rendering and 3D scene management.

Tailwind CSS: For rapid, utility-first UI styling.

HTML5 & CSS3: Core structure and glitch animations.

📦 Installation & Usage

Since this project uses CDNs for libraries, there is no complex build process (npm/webpack/vite) required.

Clone the repository:

git clone https://github.com/ramanrishit448-RR/ThreeJS.git

Open the file:
Simply double-click index.html to open it in your default web browser.

Note: For the best development experience, it is recommended to use a local server (like Live Server in VS Code) to avoid any potential cross-origin restrictions, though this specific file should work locally as-is.

🎮 Controls

Mouse Move: Rotate the central artifact.

Click "Initialize Sequence": Trigger the "Exploration Mode" (Camera zoom-in & color shift).

Resize Window: The 3D canvas automatically adjusts to the new viewport size.

🔮 Customization

You can tweak the 3D parameters in the <script> tag at the bottom of index.html:

particleCount: Change the number of background stars (Default: 2000).

isExploding logic: Change the colors triggered during the interaction sequence.

Geometry: Modify TorusGeometry or IcosahedronGeometry parameters to change the shape of the core.

📄 License

This project is open source and available under the MIT License.
