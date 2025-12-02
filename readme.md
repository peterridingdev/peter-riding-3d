# Three.js 3D Scene - First Project

![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white);

An interactive 3D scene built with Three.js featuring animated text and donuts with orbit controls. This was my first Three.js project as I'm learning 3D web graphics.

## Live Demo

[View Live](https://peter-riding-3d.vercel.app/)

## What I Built

- Custom 3D text ("peter:riding") with bevel effects
- 150 randomly positioned and scaled donuts (torus geometry)
- Matcap material for consistent lighting
- Orbit controls for interactive camera movement
- Fully responsive design (mobile & desktop)

## Tech Stack

- **Three.js** - 3D library
- **OrbitControls** - Camera interaction
- **FontLoader & TextGeometry** - 3D text rendering
- **lil-gui** - Debug UI (hidden by default)

## Key Features

- ✨ Matcap shading for polished look
- 📱 Mobile-responsive with adjusted camera positioning
- 🎮 Smooth orbit camera controls with damping
- 🎲 Randomly scattered 3D geometry
- ⚡ Optimized pixel ratio handling

## What I Learned

- Loading and rendering 3D fonts in Three.js
- Working with geometries and materials
- Implementing camera controls (OrbitControls)
- Responsive design for 3D scenes
- Matcap texturing technique

## Controls

- **Left Mouse** - Rotate the scene
- **Right Mouse / Two-finger drag** - Pan the camera
- **Scroll** - Zoom in/out

## Getting Started

### Prerequisites

- **Node.js v18+** - [Download here](https://nodejs.org)
  - This includes npm (Node Package Manager)
- A code editor like VS Code
- Git (optional, for cloning)

### Step-by-Step Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/peterridingdev/peter-riding-3d.git
   cd threejs-journey-exercise
   ```

   Or download as ZIP and extract

2. **Install project dependencies**

   ```bash
   npm install
   ```

   This reads `package.json` and installs Three.js, lil-gui, Vite, etc.

3. **Start the development server**

   ```bash
   npm run dev
   ```

   You should see output like:

   ```
   VITE v6.2.2 ready in 123 ms
   ➜ Local: http://localhost:5173/
   ```

4. **Open in browser**
   - Click the URL or manually open `http://localhost:5173`
   - You should see the interactive 3D scene

### Development Tips

- Hot Module Replacement (HMR) is enabled - changes auto-refresh
- Edit files in `src/` directory
- Static assets (fonts, textures) go in `static/` folder
- Press `Q` to stop the dev server

### Building for Production

To create an optimized build:

```bash
npm run build
```

Output files are in `dist/` - ready to deploy!

### Deploy to Vercel

Already set up with Vercel CLI:

```bash
npm run deploy
```

Or push to GitHub and connect to Vercel for automatic deployments.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
