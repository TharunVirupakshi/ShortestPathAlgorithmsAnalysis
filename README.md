# ShortestPathAlgorithmsAnalysis

This project is a web application that demonstrates and analyzes different shortest-path algorithms. The project leverages [**NetworkX**](https://networkx.org/), a Python library, to generate graphs, utilize in-built shortest path algorithms, and calculate various graph metrics on the backend. On the frontend, it uses [**vis-network**](https://visjs.github.io/) for graph visualization, making it easy to understand the algorithm's behavior on different graph structures.


   <img width="1183" alt="Screenshot 2023-10-16 at 10 15 45 AM" src="https://github.com/TharunVirupakshi/ShortestPathAlgorithmsAnalysis/assets/118896616/d6a9c57d-17da-442f-ba5d-d7c07aeca23f">
   <img width="1183" alt="Screenshot 2023-10-16 at 10 15 23 AM" src="https://github.com/TharunVirupakshi/ShortestPathAlgorithmsAnalysis/assets/118896616/017e87cb-658f-4667-b3c9-b6da6a35f41d"> 
<img width="1183" alt="Screenshot 2023-10-16 at 10 14 39 AM" src="https://github.com/TharunVirupakshi/ShortestPathAlgorithmsAnalysis/assets/118896616/56eca712-6cb7-4ca7-aee6-a3a7095c88f3">


## Features

- **Graph Generation**: Generate various types of graphs, including random, grid, and more using NetworkX.
- **Shortest Path Algorithms**: Compare the performance of different shortest path algorithms.
- **Graph Metrics**: Calculate and visualize metrics such as degree centrality, betweenness centrality, and more.
- **Interactive Visualization**: Visualize the graphs and algorithm results in an interactive way.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) for the frontend.
- [Python](https://www.python.org/) for the backend.
- Python packages: Flask, NetworkX.

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/TharunVirupakshi/ShortestPathAlgorithmsAnalysis.git
   cd ShortestPathAlgorithmsAnalysis
   ```
2. Install Frontend dependencies:
   ```bash
   cd frontend
   npm install
3. Install backend dependencies (consider using a virtual environment):
   ```bash
   cd ../backend
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
4. Start the backend server:
   ```bash
   python3 app.py
5. Start the frontend development server:
   ```bash
   cd ../frontend
   npm run dev

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/TharunVirupakshi/ShortestPathAlgorithmsAnalysis/blob/main/LICENSE) file for details.



