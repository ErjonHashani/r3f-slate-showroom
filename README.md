<div align="center">
  <h1 align="center">SLATE.3D</h1>
  <p align="center">
    <strong>A high-performance, immersive 3D E-commerce experience.</strong>
  </p>
  <p align="center">
    <a href="https://nextjs.org/">Next.js 15</a> • 
    <a href="https://docs.pmnd.rs/react-three-fiber/getting-started/introduction">R3F</a> • 
    <a href="https://ui.shadcn.com/">Shadcn UI</a> • 
    <a href="https://tailwindcss.com/">Tailwind CSS</a>
  </p>

  <p align="center">
    <img src="https://img.shields.io/badge/license-MIT-slate.svg?style=flat-square" alt="License">
    <img src="https://img.shields.io/badge/PRs-welcome-indigo.svg?style=flat-square" alt="PRs Welcome">
    <img src="https://img.shields.io/badge/dynamic/json?color=slate&label=three.js&query=version&url=https%3A%2F%2Fraw.githubusercontent.com%2Fmrdoob%2Fthree.js%2Fmaster%2Fpackage.json&style=flat-square" alt="ThreeJS Version">
  </p>
</div>

---

<div align="center">
  <img src="sneakr.png" alt="Slate 3D Demo" width="800" />
</div>

## 👟 The Vision
**Slate.3D** is an open-source architectural blueprint for modern e-commerce. It moves away from flat, 2D grid layouts and introduces a **spatial product experience**. Built with a "Modern Slate" aesthetic, it prioritizes clean lines, moody lighting, and cinematic motion.

## ✨ Key Features
- **⚛️ Universal Product Component**: A "Model-Agnostic" wrapper using `<Center>` and `<primitive>` to render any `.glb` file regardless of original scale or origin.
- **🎥 Cinematic Camera**: Scripted camera movements via `CameraControls` for seamless transitions between "The Shelf" and "The Detail View."
- **🖼️ Glassmorphism UI**: High-end floating 3D labels with real-time blur and hover-state synchronization.
- **🌗 Contextual Theming**: Scene lighting and background color interpolation based on active product selection.
- **🧩 Shadcn Integration**: Professional-grade navigation and sidebars utilizing Radix UI primitives.

## 🛠️ Tech Stack
| Category | Technology |
| :--- | :--- |
| **Core** | [Next.js](https://nextjs.org/) (App Router) |
| **3D Engine** | [React Three Fiber](https://github.com/pmndrs/react-three-fiber) |
| **3D Helpers** | [@react-three/drei](https://github.com/pmndrs/drei) |
| **Controls** | [Camera-Controls](https://github.com/yomotsu/camera-controls) |
| **UI/UX** | [Shadcn UI](https://ui.shadcn.com/) / [Tailwind CSS](https://tailwindcss.com/) |
| **Icons** | [Lucide React](https://lucide.dev/) |

## 🚀 Installation & Setup

### 1. Clone the repo
```bash
git clone [https://github.com/your-username/slate-3d.git](https://github.com/your-username/slate-3d.git)
cd slate-3d
```

### 2. Install dependencies
```bash
npm install
```
### 3. Install dependencies
```bash
npx shadcn-ui@latest add sheet button separator
```

### 4. Run the development server
```bash
npm run dev
```

##📄 License
Distributed under the MIT License. See LICENSE for more information.
