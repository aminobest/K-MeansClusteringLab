# Lab on Clustering using the K-Means algorithm

This repository contains a Python notebook for analyzing developers' behaviour based on data recorded during a programming task. The notebook imports, visualizes, and clusters developers' data based on various features. 

 - objective conduct your own data analysis using an existing implementation of the K-Means clustering Algorithm 

## Prerequisites

The notebook requires the following Python libraries to be installed:

- pandas
- numpy
- matplotlib
- sklearn
- seaborn

These can be installed using pip:

```
pip install pandas numpy matplotlib sklearn seaborn
```

## Data

The data for this notebook should be in CSV format, with the following columns:

- Developer ID: An anonymized ID assigned to each developer
- Error Frequency: Number of Coding Errors / (Number of Coding Errors + Number of Successful Compilations)
- Shortcut Usage: Number of Times Shortcuts Used / Total Number of Keypresses in the IDE
- Usage of Help Features: Number of Times Help Features Accessed / Total Number of Interactions with the IDE
- Breakpoint Usage: Number of Breakpoints Set / Total Number of Debugging Actions

The notebook expects the data file to be named `data.csv` and located in the `input/` directory.

## Usage

To run the notebook, open it in Jupyter Notebook or any other Python notebook environment, and run all cells.

The notebook will perform the following steps:

1. Import the data from `data.csv`.
2. Visualize different combinations of features with scatter plots.
3. Perform K-Means clustering on different combinations of features.
4. Visualize the clusters in a 2D scatter plot.
5. (User-provided) Reflect on the clustering results and hypotheses about the data.

## Configuration

The notebook provides options for exploring different combinations of features and the number of clusters for K-Means clustering. These options can be changed directly in the notebook.

For example, to change the number of clusters, modify the `k` variable in the `KMeans` clustering cell:

```python
k = 3 # Change this to the desired number of clusters
```

To change the features used for clustering, modify the `features_set` variable:

```python
features_set = ['Error Frequency', 'Breakpoint Usage'] # Change this to the desired set of features
```

## Further Reflections

After running the notebook, users are encouraged to reflect on the clustering results. The notebook is structured in a manner that encourages an analytical mindset, opening up for further interpretations and hypotheses about the data.

## About this Analysis

The ultimate aim of this notebook is to understand developer behavior better. By understanding the behavioral trends among developers, we can facilitate more productive and error-free coding environments.

By utilizing clustering, we allow for an exploratory approach to data analysis. This notebook does not impose strict interpretations but rather encourages users to reflect and derive their own insights based on the clustering results.