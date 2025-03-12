# Spotify Feature Collaboration Network Analysis
Constructs a graph of approximately 156,000 artists with over 300,000 collaborative connections. Analyzes for small-world properties and power law adherance.
Then, focuses on the analysis of the seed artists who topped the Spotify weekly charts, looking at the small-world properties of various genre and country subgraphs.
Investigates genre distributions and co-occurrences.
Applies the Louvain method for community detection to the chart-topper graph to analyze communities for small-world properties.

Dataset used found here: https://www.kaggle.com/datasets/jfreyberg/spotify-artist-feature-collaboration-network

---

Research paper publication efforts in progress.

Author: Raquel Ana M Bush

MTH 565 - Network Analysis

---

## Running the Notebook

1. Open the Jupyter Notebook:
```
jupyter notebook spotify_feature_network.ipynb
```
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

3. Run the cells sequentially to:
  - Load the dataset.
  - Construct and analyze the graph and subgraphs.
  - Generate insightful visualizations.
4. Interpret the results from the plots and network statistics.


