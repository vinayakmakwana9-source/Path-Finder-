# Pathfinding Visualizer (A* Algorithm)

## 📌 Overview

This project is a **Pathfinding Visualizer** built using Python and Pygame. It demonstrates how the **A* (A-star) algorithm** finds the shortest path between two points in a grid.

The visualization helps users understand how pathfinding works in real-time by interacting with a graphical grid.

---

## 🚀 Features

* Interactive grid system
* Set start and end points
* Add barriers (walls)
* Visualize A* algorithm step-by-step
* Reset grid functionality

---

## 🧠 Algorithm Used

### A* (A-Star) Algorithm

* Combines:

  * **g(n)** → cost from start to current node
  * **h(n)** → heuristic (Manhattan distance)
* Formula:

  ```
  f(n) = g(n) + h(n)
  ```

---

## 🛠️ Technologies Used

* Python
* Pygame
* Priority Queue (from queue module)

---

## ▶️ How to Run

### 1. Install dependencies

```bash
pip install pygame
```

### 2. Run the program

```bash
python main.py
```

---

## 🎮 Controls

* **Left Click**

  * First click → Set Start Node
  * Second click → Set End Node
  * Further clicks → Add barriers
* **SPACE** → Run A* Algorithm
* **C** → Clear the grid

---

## 📂 Project Structure

```
Pathfinding-Visualizer/
│── main.py
│── README.md
```

---

## 📸 Output

* Grid-based interface
* Colored nodes representing different states
* Shortest path highlighted

---

## 🎯 Applications

* Game development (NPC navigation)
* Robotics path planning
* Network routing
* AI problem-solving visualization

---

## 👨‍💻 Author

Vinayak Makwana 
