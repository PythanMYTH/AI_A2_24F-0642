# Dynamic Pathfinding Agent

## Overview
This project implements Greedy Best-First Search and A* Search in a dynamic grid environment using Pygame.

The agent can:
- Navigate from Start to Goal
- Handle dynamic obstacles
- Re-plan paths
- Switch heuristics
- Display metrics

---

## Features

- A* Search (Optimal)
- Greedy Best-First Search
- Manhattan & Euclidean heuristics
- Dynamic obstacle spawning
- Real-time visualization
- Metrics: Nodes Expanded, Execution Time

---

## Controls

A → Use A*  
G → Use Greedy  
H → Toggle heuristic  
D → Toggle Dynamic Mode  
SPACE → Start Search  
R → Reset Grid  

---

## Installation

1. Install dependencies:

pip install -r requirements.txt

2. Run:

python main.py

---

## Algorithms Implemented

Greedy Best-First Search:
f(n) = h(n)

A* Search:
f(n) = g(n) + h(n)

---

## Dynamic Mode

When enabled, obstacles spawn randomly during execution.
If a path is blocked, the agent recalculates a new path.

---

## Author

AI 2002 - Assignment 2
