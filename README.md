# Pathfinding Algorithms Visualizer
#### Welcome to the Algorithm Visualizer project! 🚀

- This project offers an interactive platform to witness the magic of graph algorithms in action.


## Screenshots

![Screenshot (371)](https://github.com/shrugi/Pathfinding-Algorithms-Visualizer/assets/119075148/7ee5a2ee-3a12-4980-bb36-a8016889bb58)
![Screenshot (372)](https://github.com/shrugi/Pathfinding-Algorithms-Visualizer/assets/119075148/d56d34e0-a946-4e1b-b293-86f1db0c3b79)
![Screenshot (373)](https://github.com/shrugi/Pathfinding-Algorithms-Visualizer/assets/119075148/7087135b-82f0-439f-b8ae-7c9f4ead93c9)


## Meet the Algorithms

### Depth-First-Search (DFS)
Traverses the graph depth-first, exploring as far as possible before backtracking.

### Breadth-First-Search (BFS)
Explores the graph level by level, visiting all neighbors before moving on to the next level.

### A* using Manhattan Distance h(n)
Heuristic-based algorithm combining Dijkstra's and greedy search, utilizing Manhattan distance as a heuristic.

### Dijkstra (Uniform-Cost-Search variant)
Finds the shortest path in a weighted graph using a priority queue for lower-cost paths.

### Greedy-Best-First Search using Manhattan Distance
Greedy algorithm prioritizing paths based on Manhattan distance to the goal.

### Bidirectional Search
Simultaneously explores from both start and end points, meeting in the middle using A* algorithm.

- **Astar:** Bidirectional exploration using A* algorithm.
- **BFS:** Bidirectional Breadth-First-Search, meeting in the middle.
- **Greedy-BFS:** Bidirectional Greedy-Best-First Search with a greedy heuristic.
- **Dijkstra (UCS):** Bidirectional Dijkstra to find the shortest path.

### Random Maze Generation Algorithms

- **Prim's Algorithm:** Generates a maze by adding random edges following Prim's algorithm.
- **Recursive Backtracker:** Uses recursive backtracking to create a maze.

### Minimum Spanning Tree Algorithms

- **Prim's Algorithm:** Finds the minimum spanning tree in a weighted, connected graph.

### Topological Sorting

- **Kahn's Algorithm:** Orders nodes in a directed acyclic graph (DAG) linearly based on dependencies.


## Features

- **Interactive Grid:** Create and customize grids for algorithm visualization.
- **Algorithm Selection:** Choose from a variety of algorithms for visualization.
- **Real-time Visualization:** Watch the algorithm's step-by-step progress in real-time.
- **Start and End Points:** Define starting and ending points for personalized scenarios.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/shrugi/Pathfinding-Algorithms-Visualizer.git
    ```

2. Navigate to the project directory:

    ```bash
    cd my-app
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Run the application:

    ```bash
    npm start
    ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to explore the algorithm visualizer.

## Available Scripts

- **npm start:** Runs the app in development mode.
- **npm test:** Launches the test runner in the interactive watch mode.
- **npm run build:** Builds the app for production to the build folder.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Acknowledgments

This project was inspired by a passion for algorithms and learning experiences from online tutorials.

Special thanks to [@hisham-maged](https://github.com/hisham-maged10) for the original Pathfinding Algorithm Visualizer project! I learned a lot from your work and it greatly influenced this project.


Happy Visualizing! 🎉✨

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
