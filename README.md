# DOOM-Style FPS Game (Python + Pygame) 🕹️

A fully playable first-person shooter built from scratch using **Python** and **Pygame**, replicating the core rendering technique used in the original DOOM (1993) — **raycasting**.

This project was created to explore game development fundamentals, 2.5D rendering, and real-time interactivity using lightweight tools and logic-based game design.

## ⚙️ Tech Stack & Tools Used

| Tool/Library     | Purpose |
|------------------|---------|
| **Python 3**     | Core programming language |
| **Pygame**       | Game development framework for handling rendering, input, and audio |
| **Raycasting**   | Used to simulate 3D walls in a 2D map layout (similar to Wolfenstein/DOOM) |
| **A* Pathfinding** | For NPC movement/navigation |
| **Procedural Map Layout** | Grid-based design for simple level logic |
| **Custom Collision Engine** | Handles player/NPC interaction with the map |
| **Sound Mixer**  | Pygame mixer module to play effects and ambient sound |

---

##  How It Works (Core Concepts)

### 🧱 1. **Raycasting Engine**
- Each frame, rays are cast from the player’s viewpoint to detect walls
- Calculates wall distance → renders vertical slices to fake depth
- Performance-friendly and visually effective

### 🤖 2. **NPC AI**
- Simple FSM (finite state machine)
- NPCs can patrol, follow, or attack player
- Uses `A*` pathfinding over a grid map

### 🔫 3. **Weapon Logic**
- Weapon sprite overlays and firing logic
- Damage, recoil, and hit detection
- Sound effects for each shot

### 🗺 4. **Map & Level Design**
- Map is represented as a 2D array
- Each cell = wall, floor, or object
- Easy to expand and create custom levels

- Demonstrates how old-school FPS games worked
- Reinforces 2D → 3D thinking via raycasting
- Builds your Python + game development credibility
- No engines or frameworks beyond `pygame`
- Clean architecture: easy to extend or rework into a larger game





