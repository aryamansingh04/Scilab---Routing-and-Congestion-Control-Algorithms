# 📡 Network Routing & Congestion Control Simulation  
### Scilab + NARVAL Toolbox Implementation

---

## 📌 Project Overview

This project implements and analyzes **Routing Algorithms** and **Congestion Control Mechanisms** using **Scilab** with the **NARVAL Toolbox**.

The objective is to simulate different network topologies, evaluate shortest-path routing performance, apply ARC-based congestion control, and analyze execution time across varying network sizes.

---

## 🛠️ Technologies Used

- **Scilab**
- **NARVAL Toolbox**
- Graph Visualization
- Performance Measurement using `timer()`

---

# 🚀 Task 1 – Routing Algorithm Analysis

## 🎯 Objectives

- Generate network topologies from **5 to 100 nodes**
- Apply:
  - **Dijkstra Algorithm**
  - **Bellman-Ford Algorithm**
- Measure execution time
- Visualize network topologies
- Plot performance comparison graph

---

## 🔍 Implementation Workflow

1. Generate topology using locality-based method.
2. Select random source node.
3. Compute shortest paths using:
   - Bellman-Ford
   - Dijkstra
4. Measure execution time (averaged over multiple runs).
5. Print results in console.
6. Plot time comparison graph.

---

## 📊 Key Observations

- Dijkstra performs significantly faster than Bellman-Ford for larger networks.
- Execution time increases as node count increases.
- Performance gap widens as network grows.

---

# 🚦 Task 2 – Congestion Control Analysis

## 🔹 Part 1: 200 → 300 Nodes

- Generate 200-node network
- Increase to 300 nodes
- Visualize both networks
- Apply ARC-based congestion control
- Measure execution duration
- Plot comparison graph

---

## 🔹 Part 2: 500 Node Network (5 Topology Methods)

Networks generated using:

- Locality
- Random
- Grid
- Small-World
- Scale-Free

For each topology:

- Visualize network
- Perform congestion mapping
- Measure execution time
- Compare performance using bar graph

---

## 🔹 Part 3: Node Reduction Analysis

Network size reduced as:
