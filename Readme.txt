# 🌀 Maze Traversal Simulator (DFS & BFS)

A console-based C++ application that visualizes the **Depth-First Search (DFS)** and **Breadth-First Search (BFS)** graph traversal algorithms solving a dynamically generated 25x25 maze in real-time. Designed specifically for Windows, it features custom console coloring, animated cursor positioning, and background audio playback.

---

## ✨ Features
* **Real-Time Visualization:** Watch the algorithm step-by-step navigate through the maze ('X').
* **Algorithm Comparison:** Easily switch between DFS (Stack-based) and BFS (Queue-based) approaches.
* **Dynamic Generation:** A fresh, unique maze is procedurally generated for every run.
* **Visual Styling:** Color-coded console UI distinguishing walls, explored paths, and the green Exit ('E').
* **Multimedia Integration:** Atmospheric background music playback during execution.

---

## 🛠️ Prerequisites & Requirements
To compile and run this project, ensure you have:
* **C++ Compiler:** GCC (via MinGW or Cygwin) recommended.
* **Operating System:** Windows OS (required for native console and multimedia headers like `windows.h` and `MMsystem.h`).
* **Audio File:** Ensure `Undertale OST - 059 Spider Dance.wav` is placed in the same directory as the executable.

---

## 🚀 How to Run & Build

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Terminator-maker/Maze-traversal-using-breadth-first-and-depth-first-search.git](https://github.com/Terminator-maker/Maze-traversal-using-breadth-first-and-depth-first-search.git)
   cd Maze-traversal-using-breadth-first-and-depth-first-search
Compile the code:(Note: The -lwinmm flag is critical to link the Windows Multimedia library for sound playback)

Bash
g++ main.cpp -o main.exe -lwinmm
Run the executable:

Bash
.\main.exe
