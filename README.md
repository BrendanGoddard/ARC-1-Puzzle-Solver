# ARC-1 Handmade Puzzle Solvers  

A fully interactive web showcase of three **manually coded ARC-1 puzzles**, built with pure JavaScript, HTML, and CSS — no ML models, just human reasoning.  
Each solver dynamically loads its JSON data, visualizes the grid, and computes the transformation logic in real time, mimicking the **Abstraction and Reasoning Corpus (ARC)** challenges by François Chollet.  

---

## Live Demo

https://arc-1-puzzle-solver.vercel.app/

<img width="1623" height="903" alt="arc-display" src="https://github.com/user-attachments/assets/908aab18-052d-476f-9204-27db57bf3334" />
---


## Project Overview
The ARC benchmark tests *systematic generalization* — how humans and machines infer abstract rules from limited examples.  
This project recreates three ARC puzzles entirely by hand-written logic to demonstrate symbolic reasoning, pattern recognition, and interactive visualization in the browser.

### Puzzles Implemented
| Puzzle ID | Name | Description |
|------------|------|-------------|
| **1cf80156** | Mirror Across Diagonal | Reflects all non-zero cells across the **anti-diagonal** within their bounding box. |
| **0ca9ddb6** | Cross & Diagonal Coloring | Puts **7s** around each **1** in a plus shape and **4s** around each **2** on the diagonals. |
| **25d8a9c8** | Monochrome Rows | If all cells in a row are identical, turns the row into **[5,5,5]**; otherwise **[0,0,0]**. |

---

## Features
- **Dynamic Grid Rendering:** Visualizes input, expected, predicted, and diff grids.
- **Live Solvers:** Each page runs the puzzle logic directly in JavaScript — no external dependencies.
- **Animated Background:** The same glowing green ARC-style background and favicon unify all pages.
- **Home Navigation:** Quick link back to the puzzle gallery.
- **Data-Driven:** Loads `.json` puzzle data for both training and test cases.

---

