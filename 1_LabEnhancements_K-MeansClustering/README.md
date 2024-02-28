# Lab Enhancemnet K-Means ReadMe

## Overview

This repository provides an in-depth exploration of K-Means clustering, a popular unsupervised learning algorithm, and introduces the concept of constrained K-Means. The ReadMe file serves as a guide to understand the contents of the repository and provides insights into the clustering methods discussed.

## Team Members

| Student Name                   | Student ID | Contribution                                           |
|---------------------------------|------------|--------------------------------------------------------|
| Luqman Syakir bin Adong         | 1201101594 | Enhanced the entire lab for K-Means Clustering (this lab.)       |
| Nurzafirah Syazana              | 1201101587 | Enhanced lab for PCA.                                  |
| Muhammad Faiez Bin Kamarul      | 1201101051 | Enhanced lab for Logistic Regression.                     |
| Afif Dzakirin Bin Mohd Azli     | 1201101864 | Enhanced lab for Linear Regression.                    |
## Contents

1. **K-Means Clustering Concept**
    - Introduction to the K-Means algorithm.
    - Tasks involved: Finding the Best Centers (Centroids) and Assigning Points to the Closest Center.
    - Visualization of the clustering process.

2. **K-Means Implementation using scikit-learn with Dummy Data**
    - Importing necessary libraries.
    - Generating dummy data based on height and weight.
    - Choosing the number of clusters (K).
    - Visualizing the clustering process.
    - Elbow Method to find the optimal number of clusters.
    - Silhouette Analysis to assess the quality of clusters.

3. **Constrained K-Means: Controlling Group Size**
    - Introduction to Constrained K-Means.
    - Real-life example: Allocating students to classrooms.
    - Generating synthetic data with distinct clusters.
    - Fitting the KMeansConstrained model.
    - Visualizing the results of constrained K-Means clustering.

4. **Evaluating Clustering Performance Using Advanced Techniques**
    - Comparison of K-Means and DBSCAN on crescent-shaped data.
    - Visualization and interpretation of results.
    - Selection of the optimal clustering method for the given dataset.

## How to Use

1. **Download ZIP:**
   - Click the "Code" button on the GitHub repository page.
   - Select "Download ZIP" from the dropdown.
   - Extract the ZIP file on your local machine.

2. **Explore the Code:**
   - Open Jupyter notebooks in your preferred environment (e.g., Jupyter Notebook, JupyterLab).
   - Navigate to the extracted repository and open the relevant notebook.

3. **Run Jupyter Notebooks:**
   - Read through the code and comments in the notebooks to understand the concepts and implementations.
   - Modify parameters, such as the number of clusters, to observe the impact on clustering results.

4. **Experiment with Constrained K-Means:**
   - Modify attributes like the number of clusters, min size, and max size in the constrained K-Means section.
   - Observe how the algorithm optimally divides data while considering size constraints.

5. **Evaluate Clustering Performance:**
   - Explore the comparison between K-Means and DBSCAN on crescent-shaped data.
   - Understand the strengths and weaknesses of each algorithm in different scenarios.

## Dependencies

Ensure you have the following Python libraries installed:

- pandas
- matplotlib
- numpy
- scikit-learn
- k_means_constrained

## Conclusion

This repository provides a comprehensive exploration of K-Means clustering, constrained K-Means, and a comparison with DBSCAN. Use the provided notebooks to learn, experiment, and understand the practical applications of these clustering techniques.

Happy Clustering!
