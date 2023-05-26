# Lab on Clustering using the K-Means algorithm


 - **Objective**: Conduct your own data analysis using an existing implementation of the K-Means clustering Algorithm 
 - **Context**: Analyying the behavioural data of developers recorded during a programming task

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

To run the notebook, you also need to have Jupyter Notebook installed. If not already installed, it can be installed using pip:

```
pip install notebook
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


1. Launch Jupyter Notebook by opening a terminal (or command prompt in Windows), navigating to the directory containing the notebook, and running the command:

```bash
jupyter notebook
```

2. In the Jupyter Notebook web interface, click on the notebook file (`K-MeansClustringNotebook.ipynb`) to open it.

3. Run the cells in the notebook sequentially 


## Tasks

The notebook contains tasks that you need to complete for this lab. 