# DSC212_Assignment
# Karate Club Graph — Network Analysis Assignment

This repository contains a Python notebook implementing network-science techniques on the classic **Zachary Karate Club Graph**. The analysis explores graph structure, computes centrality measures, performs iterative community division, and visualizes how the network evolves across splits.


## Features

### **1. Graph Construction**
- Loads the **Zachary Karate Club Graph** using NetworkX.
- Represents the social network of 34 members and their interactions.

### **2. Community Division**
- Implements a custom function to divide selected nodes into two groups based on computed metrics.
- Supports iterative splitting until a desired cluster count is reached.

### **3. Centrality Metrics**
The notebook computes several key structural measures:

- **Degree Centrality**
- **Betweenness Centrality**
- **Closeness Centrality**
- **Clustering Coefficient**

These metrics help determine influential nodes and structural roles within the network.

### **4. Visualizations**
Includes functions to generate:

- **Graph plots** showing node clusters with color-coding  
- **Metric-evolution plots** tracking how centrality values change across iterations

All visualizations can be enabled/disabled using the `show_plots` argument.


## Outputs

After running the notebook, you will obtain:

* Visualized graph states across iteration steps
* Cluster assignments for nodes
* Centrality metrics for each node
* Evolution plots showing how metrics change during community division

These outputs help illustrate how network structure changes as nodes are grouped.


## Background

The **Zachary Karate Club graph** (1977) is a widely used benchmark dataset in community detection. It represents friendships in a university karate club that eventually split into two factions.

This assignment uses the graph to explore:

* Social network structure
* Node importance
* Effects of iterative clustering
* Visualization of network evolution


## Acknowledgment

Dataset courtesy of Wayne Zachary (1977), implemented in NetworkX.
