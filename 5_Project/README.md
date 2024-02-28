# Machine Learning Project ReadMe

## Overview

This repository focuses on the analysis of KL Weather data using various data science techniques. The main sections cover preprocessing, K-Means clustering, PCA (Principal Component Analysis), linear regression, and time series analysis. The analysis includes visualization of clusters, elbow method, silhouette analysis, linear regression evaluation, and time series decomposition.

## Team Members

| Student Name                   | Student ID | Contribution                                           |
|---------------------------------|------------|--------------------------------------------------------|
| Luqman Syakir bin Adong         | 1201101594 |  Linear Regression and Interactive 3D Linear Regression Plot Implementation  |
| Nurzafirah Syazana              | 1201101587 |   Data Preprocessing and K-Means Clustering |
| Muhammad Faiez Bin Kamarul      | 1201101051 |  Principal Component Analysis (PCA) and Time Series Visualization |
| Afif Dzakirin Bin Mohd Azli     | 1201101864 | Time Series Decomposition and Correlation Heatmap |

## Contents

1. **Data Preprocessing**
    - Handling missing values for numeric columns.
    - Extracting and normalizing numeric features.
    - Categorizing columns into numeric, categorical, and time features.

2. **K-Means Clustering**
    - Implementing K-Means clustering on normalized data.
    - Visualizing clusters based on precipitation and cloud cover.
    - Elbow Method and Silhouette Analysis to find optimal clusters.

3. **Principal Component Analysis (PCA)**
    - Applying PCA for dimensionality reduction.
    - Visualizing KL Weather dataset in reduced dimensions.
    
4. **Linear Regression Implementation**
    - Selecting features and target variable for UV Index prediction.
    - Training a linear regression model.
    - Evaluating the model and visualizing actual vs. predicted UV Index.

5. **Interactive 3D Linear Regression Plot**
    - Utilizing Plotly for an interactive 3D linear regression plot.
    - Visualizing actual and predicted temperature data in a 3D space.

6. **Time Series Visualization**
    - Visualizing temperature data over time using a time series plot.
    
7. **Time Series Decomposition**
    - Decomposing temperature data into trend, seasonal, and residual components.

8. **Correlation Heatmap**
    - Creating a heatmap to visualize correlations between numerical features.

## How to Use

1. **Download ZIP:**
   - Click the "Code" button on the GitHub repository page.
   - Select "Download ZIP" from the dropdown.
   - Extract the ZIP file on your local machine.

2. **Change the Dataset filepath:**
    - Change the filepath in the Read Data section at the beginning
    - Place the correct path to access the dataset using pandas

3. **Explore the Code:**
   - Open Jupyter notebooks in your preferred environment (e.g., Jupyter Notebook, JupyterLab).
   - Navigate to the extracted repository and open the relevant notebook.

4. **Run Jupyter Notebooks:**
   - Read through the code and comments in the notebooks to understand the concepts and implementations.
   - Modify parameters, if needed, for exploration and experimentation.

## Dependencies

Ensure you have the following Python libraries installed:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- plotly
- statsmodels
- nbformat

## Conclusion

This repository provides an extensive analysis of KL Weather data, covering clustering, PCA - dimensionality reduction, linear regression, and time series visualization. Use the provided notebooks to gain insights and explore different aspects of the dataset.

Happy Exploring!
