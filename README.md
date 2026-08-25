# 🎮 Shootem

A fast-paced **top-down shooter game** built with Unity, featuring dynamic gameplay, custom shaders, and engaging combat mechanics.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Controls](#controls)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

**Shootem** is a top-down shooter game developed in Unity. Players navigate through the game world, engage enemies, and survive waves of combat in an action-packed environment. The project showcases advanced rendering techniques with custom shaders and optimized C# game logic.

---

## ✨ Features

- 🎮 **Top-Down Perspective** - Classic arcade-style gameplay
- 🔫 **Combat System** - Dynamic shooting mechanics and enemy interactions
- 🎨 **Custom Shaders** - Visual effects using ShaderLab and HLSL for enhanced graphics
- ⚡ **Optimized Performance** - Efficient C# code for smooth gameplay
- 🎯 **Enemy AI** - Challenging opponent behavior patterns
- 📊 **Score System** - Track your performance and achievements

---

## 🛠 Tech Stack

| Component | Technology | % |
|-----------|-----------|---|
| **Graphics** | ShaderLab | 62.4% |
| **Game Logic** | C# | 26.4% |
| **Rendering** | HLSL | 8.4% |
| **UI/Web** | HTML | 2.8% |

- **Engine**: Unity
- **Primary Language**: C#
- **Shader Languages**: ShaderLab, HLSL

---

## 📁 Project Structure

```
Shootem/
├── Assets/
│   ├── Scenes/              # Game scenes
│   ├── Scripts/             # C# game logic
│   ├── Shaders/             # Custom ShaderLab & HLSL shaders
│   ├── Materials/           # Shader materials
│   ├── Prefabs/             # Reusable game objects
│   ├── Sprites/             # 2D game graphics
│   └── Audio/               # Sound effects and music
├── ProjectSettings/         # Unity project configuration
├── Packages/                # Unity packages and dependencies
└── README.md                # This file
```

---

## 🚀 Getting Started

### Prerequisites

- **Unity** (version compatible with this project)
- **Git** for version control
- A compatible graphics card for shader rendering

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vEnoch24/Shootem.git
   cd Shootem
   ```

2. **Open in Unity**
   - Launch Unity Hub
   - Click "Add" and select the cloned project folder
   - Wait for Unity to import all assets and shaders

3. **Load the Main Scene**
   - Navigate to `Assets/Scenes/`
   - Open the main game scene
   - Press **Play** in the Unity Editor

### Running the Game

- **Editor Mode**: Press `Play` button in Unity Editor
- **Build**: Go to `File → Build and Run` to create a standalone build

---

## 🎮 Controls

| Action | Key |
|--------|-----|
| **Move** | WASD or Arrow Keys |
| **Shoot** | Left Mouse Button / Space |
| **Pause** | ESC or P |
| **Aim** | Mouse Movement |

*Controls may vary - check in-game settings for customization*

---

## 💻 Development

### Key Files

- **Scripts** (`Assets/Scripts/`): Core game mechanics
  - Player controller
  - Enemy AI
  - Weapon systems
  - Game manager

- **Shaders** (`Assets/Shaders/`): Visual effects
  - Custom lighting
  - Sprite effects
  - Post-processing

### Building and Testing

1. **Test in Editor**
   ```
   File → Build Settings → Play
   ```

2. **Create Build**
   ```
   File → Build Settings → Build and Run
   ```

3. **Performance Profiling**
   - Use Unity Profiler: `Window → Analysis → Profiler`

### Code Style

- Follow C# coding standards
- Use meaningful variable and function names
- Add comments for complex logic
- Ensure shader code is optimized for performance

---

## 🤝 Contributing

We welcome contributions! To contribute:

1. **Fork** the repository
2. **Create a branch** for your feature
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and test thoroughly
4. **Commit** with clear messages
   ```bash
   git commit -m "Add feature: description"
   ```
5. **Push** to your fork
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Submit a Pull Request** describing your changes

### Contribution Guidelines

- Ensure code is tested and functional
- Include shader optimization where applicable
- Update documentation if adding new features
- Follow the existing code structure and style

---

## 📝 License

This project is a fork of [OG-Enoch/Shootem](https://github.com/OG-Enoch/Shootem).

See the LICENSE file for more details.

---

## 🎓 Resources

- [Unity Documentation](https://docs.unity3d.com/)
- [ShaderLab Reference](https://docs.unity3d.com/Manual/SL-Reference.html)
- [C# Programming Guide](https://learn.microsoft.com/en-us/dotnet/csharp/)
- [Game Development Best Practices](https://unity.com/resources/best-practices)

---

## 📧 Support

For issues, questions, or suggestions:
- Open an [Issue](https://github.com/vEnoch24/Shootem/issues) on GitHub
- Check existing issues for solutions
- Provide detailed descriptions and steps to reproduce bugs

---

## 🎉 Acknowledgments

- **Original Project**: [OG-Enoch/Shootem](https://github.com/OG-Enoch/Shootem)
- **Unity Community**: For resources and best practices
- **Contributors**: All those who help improve the game

---

**Happy Shooting! 🔫**

---

*Last Updated: August 2024*
