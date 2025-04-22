# MiniGrpProject5a
# Social Network Visualization with Degree Centrality

## Project Overview
This project visualizes a social network graph where **node sizes are scaled based on degree centrality**. The objective is to intuitively represent influence and connectivity within a network by mapping the most connected nodes as larger, more prominent entities.

##  Key Concepts
- **Degree Centrality**: Measures how many direct connections a node has.
- **NetworkX**: Used to construct the graph and compute centrality scores.
- **Matplotlib**: Used for plotting the network using a spring layout.
- **Spring Layout**: A force-directed algorithm that positions nodes based on edge relationships, improving visual clarity.

##  What This Project Does
- Builds a sample social network graph.
- Computes degree centrality for all nodes.
- Scales node sizes according to centrality scores.
- Visualizes the network with a clean, intuitive layout.

##  Why It Matters
Degree centrality offers a powerful yet simple way to identify key actors in a network. By incorporating it into the visual design, the network map becomes an analytical tool—highlighting influence, bridging nodes, and hidden hubs within the system.

##  Sample Output
A rendered graph showing variable node sizes based on their degree centrality, laid out in a spring formation for optimal readability.

##  Files
- `MiniProject5a.ipynb`: The full Jupyter Notebook containing the code and visualization.
- `README.md`: Project documentation.

##  Future Extensions
- Integrate other centrality metrics (betweenness, closeness).
- Add interactivity with Plotly or PyVis.
- Apply to real-world datasets like LinkedIn or Twitter networks.


