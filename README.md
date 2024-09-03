# 🚇 Metro Route Finder - Java Project

## 🚀 Project Overview

Welcome to the **Metro Route Finder** – your smart, Java-powered companion for navigating the vast Delhi Metro network! This interactive application helps users find the **shortest metro route** between any two stations, calculating the most efficient path and the corresponding fare. Whether you're a daily commuter or a first-time traveler, this tool makes metro travel a breeze. Plus, it includes a handy metro map for easy navigation.

## 🛠️ Technical Implementation

Under the hood, this project leverages powerful data structures and algorithms:

- **Graphs**: Stations are represented as nodes, each with key details like the station name, metro corridor, and connecting lines.
- **Heaps**: Used to efficiently manage the edges (connections between stations), where each edge's cost reflects the distance between two stations.

To ensure you reach your destination quickly and cost-effectively, the application uses a combination of algorithms:

- **Dijkstra's Algorithm**: Finds the shortest path between the source and destination stations.
- **Breadth-First Search (BFS)** & **Depth-First Search (DFS)**: Employed to explore and traverse the metro network.

After calculating the total distance, the program presents the best metro route and the fare directly to the user.

## 📂 Project Structure

- **`Graph_M.java`**: The heart of the application, handling everything from user input to route calculation and fare computation.
- **`Heap.java`**: Implements the heap data structure, crucial for optimizing the shortest path algorithms.

---

Feel free to clone, fork, and contribute to the **Metro Route Finder** project. Let's make metro navigation smarter together!
