# 🧟‍♂️ Weird Monster

This repository contains a **procedural animation project** that creates an interactive *“weird monster”* using **JavaScript** and the **HTML5 Canvas**.  
The creature is built from multiple connected segments and dynamically follows the user’s mouse cursor, resulting in a smooth, organic crawling motion.

The animation is powered by a **custom physics system** and **inverse kinematics (IK)**, giving the monster a surprisingly life-like behavior.

---

## 🌐 Live Demo

Try the project live here:

👉 ****

---

## ✨ Features

- **Interactive Animation**  
  The monster actively tracks and follows the mouse cursor in real time.

- **Procedural Generation**  
  Each page load generates a unique lizard-like creature with a random number of legs and tail segments.

- **Inverse Kinematics (IK)**  
  Limbs use an IK system to calculate joint angles and place feet intelligently as the body moves.

- **Segment-Based Physics**  
  The creature is constructed from a hierarchy of `Segment` objects, enabling flexible body movement with simulated stiffness and resistance.

---

## 🚀 Getting Started

No build tools or external dependencies are required.

1. Clone the repository:
   ```bash
   git clone (https://github.com/anirudhagarwal-dev/Weird_Monster.git)