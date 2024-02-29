# Three.js Project Setup with Vite - Comprehensive Guide

## Overview

This guide provides detailed steps to set up a Three.js project using the Vite build tool. Follow the instructions below for a smooth installation process.

## Prerequisites

Ensure you have Node.js installed on your machine before proceeding with the installation.

## Installation Guide

1. **Create Project Directory**:
   ```bash
   mkdir my-threejs-project
   cd my-threejs-project
   ```
2. **Navigate to Project Directory**:
   ```bash
   cd your-repository
   ```
3. **Install Dependencies**:
   ```bash
   npm install
   ```
4. **Start Development Server**:
   ```bash
   npm run dev
   ```

# Three.js Template with Orbit Controls and Debug GUI

This Three.js template includes Orbit Controls for interactive camera movement and a Debug GUI for easy parameter adjustments. You can use this template to create 3D scenes with interactive elements and debugging capabilities.

## How to Use

1. Import the necessary libraries like Three.js, OrbitControls, dat.gui, and gsap.
2. Create a canvas element in your HTML file with the class "webgl".
3. Copy and paste the following code into your JavaScript file.
4. Customize the scene by adding objects, lights, and materials.
5. Run your project to see the interactive 3D scene with Orbit Controls and Debug GUI.

## Import Libraries

- **Three.js**: A popular 3D library for creating interactive 3D graphics in the browser.
- **OrbitControls**: Provides an easy way to control the camera and navigate around the 3D scene.
- **dat.gui**: A lightweight graphical user interface for adjusting parameters in real-time.
- **gsap**: GreenSock Animation Platform for advanced animations.

## Debug GUI

- **gui**: Initializes a dat.GUI instance for interactive parameter adjustments.

## Canvas Selection

- **canvas**: Selects the HTML canvas element with the class "webgl" for rendering the 3D scene.

## Scene Setup

- **scene**: Creates a new Three.js scene to hold all objects, lights, and cameras.

## Object Creation

- **geometry**: Defines a TorusGeometry object with specific parameters like radius and tube.
- **material**: Creates a MeshBasicMaterial for the mesh with a color of 0xffcc00 (yellow).

## Mesh Positioning

- **sphere**: Creates a mesh using the defined geometry and material, positions it in the scene at z = -3, and adds it to the scene.

## Lighting

- **pointLight**: Adds a PointLight with white color (0xffffff) and intensity 1 at position (2, 3, 4) to illuminate the scene.

## Window Resize Event

- Updates sizes and adjusts camera aspect ratio and renderer size on window resize for responsive design.

## Camera Setup

- Creates a PerspectiveCamera with a field of view of 75 degrees, aspect ratio based on window size, near clipping plane at 0.1, and far clipping plane at 100. Positions the camera at (0, 0, 2) in the scene.

## Renderer Configuration

- Configures a WebGLRenderer with alpha transparency to render the scene on the canvas element.

## Animation Loop

- Uses a clock to track elapsed time for animations.
- Updates object rotation based on elapsed time.
- Renders the scene using the renderer and camera settings in an animation loop using requestAnimationFrame.

```

```
