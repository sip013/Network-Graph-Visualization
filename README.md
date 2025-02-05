# Network Graph Visualization

## Overview
This project provides an interactive web-based visualization of a network graph. Users can specify the number of nodes and edges, then see the network structure dynamically generated on the webpage. Additionally, the implementation includes Dijkstra's Algorithm to compute the shortest paths from a selected source node.

## Features
- Interactive user input for creating nodes and edges
- Dynamic network graph visualization
- Implementation of Dijkstra's shortest path algorithm
- Displays the shortest distances from a source node to all other nodes

## Technologies Used
- HTML
- CSS
- JavaScript

## Usage
### 1. Setup
No installation is required. Simply open the `index.html` file in a browser to use the tool.

### 2. Creating a Graph
1. Enter the number of nodes (between 2 and 10).
2. Enter the source node (starting point for Dijkstra's algorithm).
3. Click the **Create Network** button to generate the graph.
4. When prompted, enter the number of edges for each node and provide the adjacent node along with edge weight.

### 3. Running Dijkstra's Algorithm
- Click the **Run Dijkstra's Algorithm** button to compute the shortest paths.
- The results will be displayed below the graph.

## Example Workflow
1. Input 5 as the number of nodes.
2. Select node 0 as the source.
3. Define edges as prompted, e.g., `1 4` (connect node 0 to node 1 with weight 4).
4. Run Dijkstra's algorithm and view the shortest distances.

## File Structure
```
|-- index.html  # Main application file
```

## Future Improvements
- Improve UI styling and responsiveness.
- Implement weighted directed graphs.
- Optimize edge drawing for better visualization.

## License
This project is licensed under the MIT License.

