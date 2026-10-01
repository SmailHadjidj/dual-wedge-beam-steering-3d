# LiDAR — Dual Rotating Wedges 3D

**Interactive 3D educational simulation developed by Smail Hadjidj**

This project provides an interactive visualization of **laser beam steering using two rotating wedge prisms (Risley prisms)**.

The goal is to make it easier to understand how the rotation of two wedge prisms combines to control the direction of a laser beam and generate different trajectories on a target plane.

## ▶ Interactive Simulation

**Launch the interactive 3D simulation:**  
[INSERT YOUR GITHUB PAGES LINK HERE]

## 🔬 How It Works

A laser beam propagates through two rotating wedge prisms before reaching a target plane.

Each wedge contributes a deflection vector. As the wedges rotate, these vectors combine and continuously change the direction of the outgoing beam.

The resulting laser spot trajectory is displayed directly on the target plane.

## 🎛 Interactive Controls

The simulation allows you to modify:

- **Wedge 1 rotation speed (ω₁)**
- **Wedge 2 rotation speed (ω₂)**
- **Relative phase (φ)**
- **Rotation direction**
- **Speed ratios between the two wedges**

Several predefined ratios are available:

- 1 : 1
- 1 : −1
- 1 : −2
- 1 : 3

You can also:

- Pause and resume the simulation
- Clear the laser trajectory
- Reset the camera
- Reset all parameters
- Rotate, zoom and pan the 3D view

## 🎯 Purpose

When working with dual rotating wedge systems, it can be difficult to mentally visualize how the two rotations combine and how this affects the laser spot.

This project was created as a simple educational tool to make this behavior more intuitive and visually understandable.

It may be useful for people interested in:

- LiDAR
- Optical scanning
- Laser beam steering
- Photonics
- Optical engineering
- Risley prism systems

## ⚠️ Important Note

This simulation uses a **simplified vector model** to visualize the combined effect of two rotating wedge prisms.

It is intended for educational and conceptual visualization.

It is **not a complete optical ray-tracing model** and does not currently calculate the full refraction of the laser beam through the prism surfaces using Snell's law and wavelength-dependent refractive indices.

## 🛠 Technology

The interactive visualization is built using:

- HTML
- CSS
- JavaScript
- Three.js
- WebGL

## 👤 Author

**Smail Hadjidj**

Interactive 3D simulation developed as a personal educational project focused on LiDAR and optical beam-steering visualization.
