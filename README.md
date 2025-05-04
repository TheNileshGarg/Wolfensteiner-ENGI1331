# 🕹️ Wolfensteiner

> README.md written by **Nilesh Garg**
> Game developed by **Abdullah**, **Abheek**, **Alex**, and **Levi**

---

## 🎮 Overview

**Wolfensteiner** is a multiplayer 3D raycasting shooter inspired by the classic Wolfenstein and DOOM engines. Designed to run inside a MATLAB App Designer environment, the game features real-time player combat, server-client networking, joystick integration, and pixel-based rendering.

It was created as a capstone-style academic project, where each team member tackled specific aspects of the stack—from server logic and rendering engines to joystick controls and physical hardware.

---

## 🧠 Key Features

* ⚔️ **Free-For-All Multiplayer** with real-time raycast rendering
* 🧱 **Custom Map Design** using grid arrays and texture-mapped walls
* 🧠 **AI/Server Logic** for combat detection and health reduction
* 🕹️ **Physical Joystick Support** with Arduino + Serial Communication
* 📡 **Networked Client Architecture** using MATLAB TCP/IP sockets
* 🎨 **Sprite Textures and Assets** loaded through asset manager

---

## 👥 Team Roles & Contributions

* **Abdullah** – Server Combat Logic, Networking, Joystick Site, Map Design
* **Abheek** – Health Bar Circuit (YBR), Arduino Serial Code, Map Design, Gameplay Code
* **Alex** – Physical Game Controller (CAD + 3D Printing), Sprite & Texture Design
* **Levi (SNO)** – Rendering Engine, Networking, Asset Handling, Input Handling, Map Design

> **Nilesh Garg** – Project Manager & Documentation Lead: Orchestrated contracts and partnerships, managed project roadmap and deliverables, coordinated cross-functional teams, led marketing & launch strategy, and authored comprehensive documentation.

---

## 🧠 Algorithm & Architecture

The core loop of Wolfensteiner is built using raycasting logic adapted for MATLAB's graphical capabilities. The player class handles:

* 📥 Inputs (keyboard, joystick)
* 🎯 Ray angle calculation
* 🧱 Wall collision checks
* 🎨 Rendering frame
* 📡 Sending player states to server

Meanwhile, the server performs:

* Player position sync
* Health tracking and combat detection
* Communication with all clients

---

## 📁 File Structure

```bash
📦Wolfensteiner/
├── assets_manager.py       # Loads textures and sprites
├── config.py               # Networking and render configs
├── entity.py               # Game object base class
├── joystick_server.py      # Handles physical joystick input via serial
├── map.py                  # 2D grid layout of the game world
├── network.py              # TCP/IP client networking code
├── out.json / out.txt      # Debug output files
├── player.py               # Player logic including rendering and combat
├── remote_player.py        # Tracks other players over the network
```

---

## 📺 YouTube Commercial

Check out our official commercial here:

> [https://youtu.be/n2bz3tyaXrI?si=m7ZaiV9dMk5CNMAg](https://youtu.be/n2bz3tyaXrI?si=m7ZaiV9dMk5CNMAg)

---

## 📚 New Skills Learned

* Real-time rendering in MATLAB (App Designer + image processing)
* Socket programming in MATLAB
* Arduino Serial communication
* Physical controller integration with MATLAB
* Team-based software development & GitHub workflows

---

## 💬 Contact

Feel free to reach out for more details, collaboration inquiries, or project presentations.

---
