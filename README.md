# Apprentissage Non Supervisé

This repository contains practical work (TP) for unsupervised learning, including Principal Component Analysis (PCA) and Clustering algorithms.

## Repository Structure

- **TP1/**: Principal Component Analysis (PCA) exercises
  - `TP_PCA_template.ipynb`: Main notebook for PCA implementation
  - `temperatures.csv`: Temperature data by city
  - `decathlon_JO.txt`: Olympic decathlon data
  - `activites.txt`: Daily activities dataset

- **TP2/**: Clustering exercises
  - `TP_clustering_template.ipynb`: Main notebook for clustering algorithms
  - `hotels.csv`: Hotel data for clustering analysis

## Setup Instructions

### Creating and Activating Virtual Environment

#### Option 1: Using VS Code Command Palette (Recommended)
1. Open VS Code in the project directory
2. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)
3. Type "Python: Create Environment" and select it
4. Choose "Venv" as the environment type
5. Select your preferred Python interpreter
6. Wait for the environment to be created

#### Option 2: Using Terminal
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows (Git Bash)
source venv/Scripts/activate

# On Windows (Command Prompt)
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate
```

### Installing Dependencies

Once your virtual environment is activated, install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter scipy
```

### Selecting Python Interpreter in VS Code

1. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)
2. Type "Python: Select Interpreter" and select it
3. Choose the interpreter from your virtual environment (should show the project path)

## Required Libraries

- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **matplotlib**: Basic plotting
- **seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning algorithms (PCA, clustering, preprocessing)
- **scipy**: Scientific computing (hierarchical clustering)
- **jupyter**: Notebook support

## Usage

1. Ensure your virtual environment is activated
2. Open the desired notebook in VS Code
3. Select the correct Python interpreter (from your venv)
4. Run the cells sequentially

## Topics Covered

### TP1 - Principal Component Analysis (PCA)
- Data standardization and preprocessing
- PCA implementation and interpretation
- Scree plots and explained variance
- Principal component visualization
- Correlation circles
- Multi-dataset analysis

### TP2 - Clustering
- Data exploration and correlation analysis
- Hierarchical agglomerative clustering
- Dendrogram analysis
- K-means clustering
- Cluster evaluation (silhouette score, ARI)
- Optimal cluster number determination
