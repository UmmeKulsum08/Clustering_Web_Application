# Clustering_Web_Application
## Overview
This Clustering Web Application is a Streamlit-based interactive tool that enables users to upload dataset, preprocess data, and apply various clustering algorithms for insightful analysis. The app allows users to explore clustering models, visualize data relationships, and compare model performance to determine the best-performing clustering approach.

## Key Features
✅ Dataset Upload – Supports uploading an Excel file (World Development Measurement dataset).
✅ Data Preprocessing – Handles missing values, encodes categorical data, and standardizes numerical features.
✅ Clustering Algorithms – Implements:
     * K-Means Clustering (with Elbow Method for optimal n_clusters)
     * Agglomerative Hierarchical Clustering (with Dendrogram visualization)
     * DBSCAN (with automatic parameter tuning for eps and min_samples)
     * Gaussian Mixture Model (GMM)
          ✅ Performance Evaluation – Computes Silhouette Score, Davies-Bouldin Score, and Calinski-Harabasz Score.
          ✅ Model Visualization –
     * PCA-based 2D scatter plots for clusters
     * Dendrogram for hierarchical clustering
     * Feature distribution histograms
     * Correlation heatmap for data relationships
          ✅ User-Controlled Model Selection – Allows users to:
         * Select clustering algorithms
         * Set the number of clusters (where applicable)
         * Choose truncation level for dendrograms
           ✅ Model Comparison & Best Model Selection –
     *  Dynamically updates as models get trained
     *  Stores trained models and compares their performance
     *  Displays a comparison bar chart and highlights the best-performing model

## How to Use
1️⃣ Upload your dataset (Ensure it matches the expected format).
2️⃣ Select a clustering model from the dropdown.
3️⃣ Set parameters (number of clusters, dendrogram truncation level, etc.).
4️⃣ Click 'Train Model' to fit the selected model.
5️⃣ Visualize results with PCA plots, dendrograms, and feature distributions.
6️⃣ Compare models and identify the best-performing clustering algorithm.

## Tech Stack
* Python
* Streamlit (for UI)
* Pandas & NumPy (for data handling)
* Scikit-learn (for clustering algorithms & metrics)
* Matplotlib & Seaborn (for visualizations)
* SciPy (for hierarchical clustering & dendrograms)

## Future Enhancements
🚀 Auto-tuning of clustering hyperparameters
🚀 Interactive 3D clustering visualization
🚀 More clustering algorithms (e.g., Spectral Clustering, OPTICS, etc.)
🚀 Improved data preprocessing (outlier handling, feature selection, etc.)
