# Interactive Rolling Sphere

An interactive, physics-based 3D rolling sphere simulation in the browser, built with [Three.js](https://threejs.org/).  
Move, spin, and flick the sphere realistically using your keyboard or mouse—experience true Newtonian motion, inertia, and minimal friction, all in an endless open world.

## 🟠 Features

- **Real Physics:**  
  The sphere obeys Newton's laws with inertia, mass, friction, and rolling torque.
- **Open World:**  
  An infinite plane—no boundaries to stop your sphere.
- **Intuitive Controls:**  
  - **Mouse:**  
    Drag the sphere to "flick" it in any direction, just like rolling a real ball on a surface.
  - **Keyboard:**  
    - Arrow keys apply directional forces—roll forward, backward, or sideways.
    - Hold both left/right or up/down arrows to spin the sphere in place (horizontal/vertical spin).
  - Inertia and friction ensure the ball moves and slows down naturally.
- **Camera:**  
  The camera automatically follows the sphere, always keeping it in view.
- **Minimal UI:**  
  Simple, fullscreen experience with a clear, unobtrusive interface.
- **Responsive:**  
  Adapts to any screen size.

## 🚀 Demo

> Coming soon!

## 🕹️ Controls

| Action                        | How to do it            | Result                                      |
|-------------------------------|-------------------------|---------------------------------------------|
| Flick sphere                  | Drag with mouse         | Ball rolls with realistic inertia & spin    |
| Roll sphere forward/backward  | Up / Down arrow keys    | Ball rolls in respective direction          |
| Roll sphere left/right        | Left / Right arrow keys | Ball rolls left or right                    |
| Spin in place (horizontal)    | Hold Left + Right arrows| Ball spins horizontally                     |
| Spin in place (vertical)      | Hold Up + Down arrows   | Ball spins vertically                       |
| Fullscreen mode               | Click "Fullscreen"      | Immersive experience                        |

## 🛠️ How It Works

- Uses Three.js for rendering and scene management.
- Newtonian equations for force, velocity, torque, and angular motion.
- Mouse and keyboard input are mapped to real-world physics (impulse, force, torque).
- Ball and camera movement are decoupled—camera smoothly follows the sphere.
- Minimal friction coefficient for a near-perfect rolling experience.

## 💻 Installation & Running Locally

1. Clone the repo:
    ```sh
    git clone https://github.com/HyperBayIsLive/Interactive-rolling-sphere.git
    cd Interactive-rolling-sphere
    ```
2. Open `index.html` in your favorite browser (no build step required).

    > **Note:** For best results, use Chrome, Edge, or Firefox with WebGL enabled.

## 📦 Dependencies

- [Three.js](https://threejs.org/) (loaded via CDN)

## 📚 Project Structure

```
.
├── index.html      # Main app (Three.js logic, physics, UI)
└── README.md       # This file
```

## 📝 License

MIT License.  
Feel free to fork, extend, or use as a starting point for your own physics-based web projects!

---

**Made with ❤️ by [HyperBayIsLive](https://github.com/HyperBayIsLive)**
