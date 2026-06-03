# Eulerian Graph Algorithms in C

### 🧮 Discrete Mathematics & Graph Theory Portfolio

This repository features a robust implementation of **Eulerian Path and Circuit discovery algorithms** written in pure C. It highlights advanced tracking of vertex degrees, connectivity validations, and path-finding traversals within undirected or directed graph structures.

An **Eulerian Trail** is a trail in a finite graph that visits every edge exactly once, while an **Eulerian Circuit** is an Eulerian trail that starts and ends on the same vertex.

---

## ⚙️ Core Algorithmic Engineering

The implementation focuses on the structural conditions required to determine and map Eulerian traits:
- **Degree Verification:** Computes the degree of every vertex to quickly evaluate Eulerian existence (e.g., checking if the count of vertices with odd degrees is exactly 0 or 2).
- **Connectivity Validation:** Ensures all edges belong to a single connected component using foundational graph search traversals.
- **Path Generation:** Implements structured edge deletion and tracking cycles (utilizing concepts similar to Hierholzer's linear-time algorithm $O(E)$).

---

## 🛠️ How to Compile and Run

This project utilizes an automated `Makefile` to simplify binary compilation and lifecycle management.

### Prerequisites
- GCC Compiler (`gcc`)
- GNU Make (`make`)

### Building the Project
To compile the source code and generate the executable, run:
```bash
make
