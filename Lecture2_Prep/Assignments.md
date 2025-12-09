# Lecture 2 – Preparation Questions 

## 3.1 Graph Basics

### 1. In your own words, what is a graph?
Describe what nodes and edges are, and give one game example (e.g., nodes = rooms, edges = doors).

**Answer:**  
-  
-  
-  

---

### 2. What is the difference between a weighted and an unweighted graph?
Give an example of what the weight could represent in a game level.

**Answer:**  
-  
-  

---

### 3. Representing a simple game level  
Think of a simple level from a platformer, dungeon, etc.

How could you represent that level as:

#### • A grid graph?
**Answer:**  
-  
-  

#### • A waypoint graph?
**Answer:**  
-  
-  

---

## 3.2 Shortest Paths and Cost

### 4. Grid with cost = 1 per move (up/down/left/right)
- If you go from **(0, 0) → (0, 5)** with no obstacles, what is the path cost?  
- If you go from **(0, 0) → (3, 4)** (no diagonals, no obstacles), what is the shortest possible path cost?

**Answer:**  
- Path cost (0,0 → 0,5):  
- Path cost (0,0 → 3,4):  

---

### 5. Why might we want different movement costs on some edges?
Example: walking on a road vs walking through mud or water.

**Answer:**  
-  
-  

---

## 3.3 A* Intuition

### 6. In the A* formula `f(n) = g(n) + h(n)`:
- What does **g(n)** represent in a game grid?  
- What does **h(n)** represent?  

**Answer:**  
- g(n):  
- h(n):  

---

### 7. Enemy unit on a tile map
- If we only look at **g(n)** (actual distance from start), which classic algorithm does that resemble?  
- If we only look at **h(n)** (estimated distance to goal), what might go wrong?

**Answer:**  
- Only g(n):  
- Only h(n):  

