# Clustering_assign



This Python script evaluates KMeans, Hierarchical, and MeanShift clustering on the Iris dataset.

It tests various preprocessing methods: None, Normalization, Transform (sqrt(abs())), PCA (2 components), Transform+Normalize, and Transform+Normalize+PCA (2 components).

For each combination, it calculates the Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Index.

**Libraries:** scikit-learn, pandas, numpy.

**Usage:**
1. Install dependencies: `pip install scikit-learn pandas numpy`
2. Run the script: `python your_script_name.py`

The results are printed as a pandas DataFrame, showing the performance of each clustering setup. This helps in comparing different approaches.
