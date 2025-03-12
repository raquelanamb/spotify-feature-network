# Spotify Feature Collaboration Network Analysis
This project constructs and analyzes a Spotify artist collaboration network, containing ~156,000 artists and 300,000+ connections. Using network science techniques, it investigates small-world properties, power-law degree distribution, and community structures.
- Examines the giant component and subgraphs based on genres & country-specific charts.
- Applies Louvain community detection to identify collaboration clusters.
- Investigates genre distributions and co-occurrences among chart-topping artists.

This project utilizes the Spotify Artist Feature Collaboration Network dataset from Kaggle: 
https://www.kaggle.com/datasets/jfreyberg/spotify-artist-feature-collaboration-network

---

Research paper publication efforts in progress.

Author: Raquel Ana M Bush

Project begun for course: MTH 565 - Network Analysis (under Professor Dana Fine, University of Massachusetts Dartmouth)

---

## Running the Notebook

1. Open the Jupyter Notebook:
  ```
  jupyter notebook spotify_feature_network.ipynb
  ```
(if needed, first install Jupyter Notebook: ```pip install notebook```)

2. Install dependencies:
  ```
  pip install pandas
  pip install networkx
  pip install numpy
  pip install matplotlib
  pip install scipy
  pip install scikit-learn
  pip install community
  pip install py4cytoscape
  ```

3. Modify the following lines in the notebook to point to your local dataset paths:
  ```
  nodes_path = "your_nodes.csv_file_path"
  edges_path = "your_edges.csv_file_path"
  ```

4. Run the cells sequentially to:
  - Load the dataset.
  - Construct and analyze the graph and subgraphs.
  - Generate visualizations of communities, distributions, clustering, and diameter properties.

5. Interpret the results from the plots and network statistics. I've included guidance in markdown throughout.


