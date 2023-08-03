---
title: "Artificial Intelligence - Search"
excerpt: "An exploration of various search algorithms to include BFS, DFS, A*, Bidirectional Search."
collection: portfolio
---

# Project Overview
I'm thrilled to share a project I completed during the Summer of 2022, which involved implementing advanced informed search algorithms for optimizing driving routes in a map of Romania. The goal was to find the shortest path between two points with minimal time and space cost, demonstrating efficient runtime and memory management.

Key Highlights:

1. Priority Queue Optimization (Warmup 1) [5 Points]

Developed a custom priority queue with O(1) insertion and O(log n) removal time.
Utilized the heapq library and maintained FIFO order for nodes with the same priority.
2. Breadth-First Search (Warmup 2) [5 Points]

Implemented breadth-first search algorithm for graph traversal.
Ensured exploration of neighbors in alphabetical order for consistency.
Utilized graph.explored_nodes to track node exploration.
3. Uniform-Cost Search (Warmup 3) [10 Points]

Implemented uniform-cost search using a priority queue for optimal path finding.
Calculated edge weights using graph.get_edge_weight for accurate exploration tracking.
4. A Search (Warmup 4)* [10 Points]

Implemented A* search with Euclidean distance heuristic.
Utilized graph.nodes[n]['pos'] for heuristic distance calculation.
5. Bidirectional Uniform-Cost Search (Exercise 1) [20 Points]

Designed bidirectional uniform-cost search for improved search efficiency.
Conducted simultaneous searches from start and end states to converge on optimal path.
6. Bidirectional A Search (Exercise 2)* [29 Points]

Implemented bidirectional A* search with heuristic for both directions.
Optimized path finding by considering heuristic estimates from both ends.
7. Tridirectional UCS Search (Exercise 3) [12 Points]

Developed tridirectional search by expanding from each goal node.
Integrated uniform-cost search approach for connecting three nodes.
8. Upgraded Tridirectional Search (Exercise 4) [8 Points]

Enhanced tridirectional search performance by devising advanced strategies.
Explored techniques such as landmarks, triangle inequality, and shortcuts.
9. Race for Extra Credit (Bonus Points)

Participated in the extra credit race by implementing custom_search with innovative strategies.
Leveraged Atlanta Pickle data to optimize path planning and achieve bonus points.
This project showcases my ability to implement and optimize various informed search algorithms, enhance search efficiency, and apply creative problem-solving to real-world challenges. The emphasis on efficient memory usage, accurate exploration tracking, and strategic search techniques highlights my skills in algorithm design and optimization.