
# 🤖 A* vs. Depth-Limited Search: A Pathfinding Algorithm Comparison

This repository presents a comprehensive comparison of two popular search algorithms in Artificial Intelligence — **A\*** and **Depth-Limited Search (DLS)** — applied to grid-based pathfinding. The project evaluates their efficiency, optimality, and memory usage across different scenarios to help understand their practical trade-offs. 🚀

## 🔍 Key Highlights

- **A\* Search**: An informed algorithm using heuristics (like Manhattan distance) to find the shortest path efficiently.  
- **Depth-Limited Search (DLS)**: A depth-first search variant that avoids infinite loops using a fixed depth limit.  
- **Side-by-Side Comparison**:
  - ⏱️ *Time Complexity* — Measures the time taken to find paths.
  - 🧠 *Space Complexity* — Evaluates memory consumed during the search.
  - 🏁 *Optimality* — Checks if the shortest path is guaranteed.
- **Visual Demo**: Simulates both algorithms solving pathfinding problems on a grid with obstacles.

---

## 💻 Tech Stack

| Tool/Language | Purpose                                      |
|---------------|----------------------------------------------|
| Python        | Core programming language                    |
| `heapq`       | Priority queue implementation for A\*        |
| `matplotlib`  | Optional visualization of search paths       |
| `memory_profiler` | Used to analyze memory usage           |
| Built-in data structures | Lists, dictionaries, queues, etc. |

---

## 📊 A* vs. DLS — Performance Comparison

| Metric          | A* Search                      | Depth-Limited Search (DLS)         |
|-----------------|--------------------------------|------------------------------------|
| **Speed**       | Fast (uses heuristic)          | Slower (blind exploration)         |
| **Memory Use**  | Higher (open & closed lists)   | Lower (uses stack, limited depth)  |
| **Optimality**  | ✔ Yes (shortest path)          | ✖ Not guaranteed                   |
| **Completeness**| ✔ Yes (if heuristic is admissible) | ✖ No (may miss solution if depth too small) |
| **Use Case**    | Complex maps, guaranteed path  | Simple, shallow depth problems     |

---

## ▶️ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/ABHISHEKJULA07/A-star-vs-Depth-Limited-Search
   cd A-star-vs-Depth-Limited-Search


2. Run the script

   ```bash
   python main.py
  

3. Observe printed paths and comparison results (e.g., time, space, depth).

---

---

## 👨‍💻 Developed By

**Abhishek Jula** 

🔗 [LinkedIn](https://www.linkedin.com/in/abhi-jula0711)  
💻 [GitHub](https://github.com/ABHISHEKJULA07)  
🌐 [Portfolio](https://abhipinku66.wixsite.com/07112000)  
📧 abhishekjula018@gmail.com



