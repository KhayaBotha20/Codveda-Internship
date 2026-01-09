# Unsupervised Learning Task (Intermediate Level)

## Objective
Demonstrate understanding of unsupervised learning by identifying patterns and structures in unlabeled data.

## Key Tasks
1. **Iris Clustering**:
   - Dataset: iris.csv
   - Goal: Group iris flowers into clusters without using species labels.
   - Steps:
     - Load and preprocess data (standardize features).
     - Apply K-means or hierarchical clustering.
     - Determine optimal number of clusters (elbow method, silhouette score).
     - Visualize clusters in 2D (using PCA if needed).
     - Compare clusters to actual species for validation.

2. **Stock Price Dimensionality Reduction**:
   - Dataset: Stock Prices Data Set.csv
   - Goal: Reduce high-dimensional stock data to key components.
   - Steps:
     - Load and explore time series data.
     - Apply PCA or t-SNE for dimensionality reduction.
     - Visualize reduced dimensions.
     - Analyze correlations and identify patterns.

3. **Sentiment Topic Modeling**:
   - Dataset: Sentiment dataset.csv
   - Goal: Discover topics or themes in text data.
   - Steps:
     - Preprocess text (tokenization, stopword removal, TF-IDF).
     - Apply LDA (Latent Dirichlet Allocation) for topic modeling.
     - Determine number of topics.
     - Visualize topics and word distributions.
     - Interpret and label topics.

## Datasets Location
Datasets are in `../Data Set For Tasks/Data Set For Task/`.

## Tools and Libraries
- Scikit-learn for clustering/PCA
- Pandas/NumPy for data handling
- Matplotlib/Seaborn/Plotly for visualization
- NLTK for text preprocessing
- Jupyter for notebooks

## Deliverables
- Python scripts or notebooks for each task.
- Visualizations of clusters/topics.
- Analysis of results and insights.