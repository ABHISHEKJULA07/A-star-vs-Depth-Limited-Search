# 🔍 Performance Comparison: A* vs Depth-Limited Search

A focused comparative study of two classic search algorithms — **A\*** and **Depth-Limited Search (DLS)** — evaluating their efficiency, optimality, memory usage, and practical trade-offs in pathfinding scenarios.

This project includes modular Python implementations of both algorithms, with flexible input formats (mazes and graph structures), customizable parameters (like depth limits), and visual performance metrics such as steps taken, cost returned, execution time, and memory usage. It is ideal for students, researchers, and enthusiasts exploring search strategies in AI or graph theory.

## 🧠 Algorithms
- **A\*** uses the heuristic-driven formula `f(n) = g(n) + h(n)`, ensuring optimal paths when the heuristic is admissible.
- **Depth-Limited Search (DLS)** performs a depth-first traversal up to a specified depth, ideal for large or infinite search spaces with low memory requirements.

## 📊 Features
- Clean CLI-based usage and modular code
- Accepts mazes and graph input formats
- Tracks pathfinding stats: steps, time, memory, path cost
- Includes sample results and visualizations
- Easily extendable to add BFS, DFS, IDA*, etc.

## ⚙️ Tech Stack
| Tool           | Purpose                          |
|----------------|----------------------------------|
| **Python**     | Core logic and experimentation   |
| **NumPy**      | Data processing (optional)       |
| **Matplotlib** | Performance visualization        |
| **psutil**     | Memory tracking (optional)       |

## 📦 Usage
```bash
git clone https://github.com/ABHISHEKJULA07/A-star-vs-Depth-Limited-Search
cd A-star-vs-Depth-Limited-Search

# Run A*
python main.py --algorithm astar --input maps/maze1.txt

# Run DLS with depth limit
python main.py --algorithm dls --limit 10 --input maps/maze1.txt
