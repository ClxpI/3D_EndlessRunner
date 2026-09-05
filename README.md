# 3D Endless Runner Engine

[![Engine: Unity](https://img.shields.io/badge/Unity-100000?style=flat&logo=unity&logoColor=white)](#)
[![Language: C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

> **Executive Summary:** A fast-paced, 3D endless runner game engineered in Unity using C#. This project demonstrates core game development mechanics, including physics-based player controllers, dynamic procedural obstacle generation, and real-time UI score tracking within a 3D environment.

## 🎮 Gameplay Demonstration

Watch the gameplay in action here:  
https://github.com/user-attachments/assets/4d0fee50-a8d7-4927-a7c8-cd18b9e8955b

---

## 💻 Tech Stack & Architecture

*   **Game Engine:** Unity 3D
*   **Scripting Language:** C# (Object-Oriented Programming)
*   **Core Systems:** Unity Physics (Rigidbody), Input System, Unity UI (TextMeshPro)

### Key Engineering Concepts Applied

*   **Dynamic Procedural Generation:** Implemented `ObstacleSpawner.cs` to handle the instantiation of obstacles at randomized intervals and vector positions, creating a continuous and unpredictable gameplay loop.
*   **Physics-Based Movement Controller:** Engineered `PlayerMovement.cs` to leverage Unity's physics engine, handling rigid body forces, collision detection, and responsive input handling for fluid player traversal.
*   **Camera Tracking Logic:** Developed `CameraFollow.cs` using LateUpdate mechanics to ensure smooth, jitter-free tracking of the player entity across the z-axis.
*   **Game State & UI Management:** Built a decoupled `ScoreManager.cs` to track player progression and interface directly with Unity's UI canvas system for real-time visual updates.

---

## 📂 Repository Structure & Asset Architecture

The project adheres to strict Unity asset management protocols, ensuring a modular and highly maintainable codebase.

*   `Assets/Scripts/`: Contains the core C# logic driving the game engine.
*   `Assets/Prefabs/`: Contains pre-configured, instantiated game objects (Player, Obstacles).
*   `Assets/Materials/`: Contains custom rendering materials (e.g., Neon properties) defining the game's aesthetic.

---

## 🚀 Getting Started

### Prerequisites

*   Unity Editor (Ensure you have a compatible version installed via Unity Hub)
*   Git

### Installation & Execution

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/[YOUR_GITHUB]/3D_EndlessRunner.git
```
