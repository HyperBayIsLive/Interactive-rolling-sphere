# Interactive Rolling Sphere

An interactive, physics-accurate 3D rolling sphere simulation in the browser, built with [Three.js](https://threejs.org/).  
The sphere rolls, spins, and reacts to your keyboard and mouse with real inertia and friction, all in an endless open world.

---

## 🎮 Features

- **Realistic Rolling Physics:**  
  Sphere motion (by keyboard or mouse) is always accompanied by physically accurate rolling animation—no sliding.
- **Intuitive Controls:**  
  - **Arrow keys:** Apply directional forces to roll the ball forward, backward, left, or right. Reverse direction to slow down and stop.
  - **Mouse drag:** Hold and drag the ball to "push" it around with your virtual hand, as if rolling a real ball—feels natural and responsive.
  - **Spin in place:** Hold both left + right or up + down arrows to spin the sphere about its axis.
- **Endless Open World:**  
  The ground is an infinite plane—no boundaries, just roll forever.
- **Automatic Camera:**  
  Camera follows the ball from behind and above, always keeping it in view.
- **Minimal UI:**  
  Clean, fullscreen experience with a single "Fullscreen" button.

---

## 🕹️ Controls

| Action                          | How to do it                | Result                                                |
|----------------------------------|-----------------------------|-------------------------------------------------------|
| Roll forward/back/left/right     | Arrow keys                  | Ball rolls & animates in that direction               |
| Slow down or stop                | Arrow key opposite motion   | Ball slows and stops with realistic inertia           |
| Spin in place (horizontal/vert.) | Hold L+R/Up+Down arrows     | Ball spins in place                                   |
| Roll with mouse                  | Drag ball with left mouse   | Ball follows cursor as if "pushed" by your hand       |
| Fullscreen mode                  | Click "Fullscreen" button   | Immersive experience                                  |

---

## 🚀 Getting Started

1. **Clone or Download:**
    ```sh
    git clone https://github.com/HyperBayIsLive/Interactive-rolling-sphere.git
    cd Interactive-rolling-sphere
    ```
2. **Open `index.html` in your browser.**
    - No build step needed.
    - For best results, use Chrome, Firefox, or Edge.

---

## 📦 Dependencies

- [Three.js](https://threejs.org/) (CDN, no installation required)

---

## 🛠️ How It Works

- Uses real Newtonian physics for force, velocity, and rolling.
- The sphere's rotation is always synchronized with its movement for perfect rolling.
- Mouse drag calculates a physical force as if you’re pushing the sphere.
- Friction and inertia are modeled for realistic slow-down and stopping.
- Camera movement is smooth and dynamic.

---

## 📝 License

MIT License  
Feel free to fork, extend, and use as inspiration for your own web physics projects!

---

**Made by [HyperBayIsLive](https://github.com/HyperBayIsLive)**
