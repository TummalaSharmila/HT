
## **COURSE NAME AND CODE:** COMP ANALY HIGH-TP BIOMED DATA: 25499

### **Programmer:** Sharmila Tummala

Date: 04/24/2025

### **Programming Language:** 
Python

### **Python version:** 
Python 3.11.11

### **Description:** 
This project involves network-based analysis of human protein-protein interactions (PPI) using graph theory and statistical testing to understand the topology and connectivity within biological networks.

The analysis is divided into two main parts:

Part 1: Network Topology Analysis
Objective:
To compute core structural properties of the human protein interaction network and determine if it exhibits a scale-free topology.

Input File:
Human-PPI.txt: A tab-separated file listing binary interactions between human proteins (OFFICIAL_SYMBOL_A, OFFICIAL_SYMBOL_B).

Steps Performed:
Network Construction:

Built an undirected graph using NetworkX where each protein is a node and each interaction is an edge.

Computed Metrics:

Degree of each node: Number of direct connections (interacting partners).

Clustering Coefficient of each node: Measures how interconnected a node’s neighbors are.

Average Clustering Coefficient:

Calculated as the mean of all individual clustering coefficients in the graph.

Scale-Free Structure Test:

Plotted the degree distribution on a log-log scale to visually assess whether the network follows a power-law distribution, a characteristic of scale-free networks.

Part 2: Shortest Path Analysis and Statistical Comparison
Objective:
To assess interconnectivity and distance between proteins in two user-defined sets and statistically compare the shortest path distributions.

Input Files:
protein-list1.txt: Set A — list of proteins.

protein-list2.txt: Set B — another list of proteins.

Human-PPI.txt: Used again to construct the global PPI network.

Steps Performed:
Subgraph Construction:

Built a PPI graph using Human-PPI.txt.

Extracted shortest paths between every pair of proteins where one protein is from list 1 and the other from list 2.

Shortest Path Length Calculation:

Measured all shortest path lengths using Dijkstra’s algorithm (or BFS for unweighted graphs).

Collected the path length distribution between the two groups.

Statistical Testing – Wilcoxon Rank-Sum Test:

Compared shortest path lengths (between-group) using a Wilcoxon test to determine if there's a significant difference in connectivity patterns.


### Packages needed: 
This python code needs pandas, networkx, scipy.stats, numpy and matplotlib

### How to run my program
I am submitting a google colab file in this zip file you can run it by clicking on the link in the .ipynb file
Upload the required input files


if you are using VScode
1. make sure the python extension is installed
2. download .ipynb file and open it using VScode and run the program by clicking on the run button present on the top right corner

### NOTE
1. Python has various IDEs, running this python file completely depends on the IDE you are using.
2. Keep python file and input files in the same folder.
3. If you can't access the file please give full file path 
