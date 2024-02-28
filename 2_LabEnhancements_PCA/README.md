# Lab Enhancement: Principal Component Analysis (PCA)

## Overview

This repository delves into advanced concepts of Principal Component Analysis (PCA) by applying them to real-world datasets, demonstrating how these materials can be practically utilised. The ReadMe file acts as a guide to comprehend the repository's contents and offers insights into the discussed clustering methods.

## Team Members

| Student Name                    | Student ID | Contribution                                           |
|---------------------------------|------------|--------------------------------------------------------|
| Nurzafirah Syazana   | 1201101587 | Enhanced lab for PCA.  (this lab.)                                |
| Luqman Syakir bin Adong         | 1201101594 | Enhanced lab for K-Means Clustering.        |
| Muhammad Faiez Bin Kamarul      | 1201101051 | Enhanced lab for Logistic Regression.                  |
| Afif Dzakirin Bin Mohd Azli     | 1201101864 | Enhanced lab for Linear Regression.                    |
 
## Contents

1. **Principal Component Analysis (PCA) Concept**
    - Introduction to PCA and Principal Components
    - Understanding Dimensionality Reduction and Feature Extraction
    - Benefits of Using PCA 
    - Application of PCA
    - Glossary (Common Terms)

2. **Steps to Perform PCA**
    - Data Standardization
    - Covariance Matrix Computation
    - Eigenvalue and Eigenvector Decomposition
    - Selecting Principal Components
    - Data Transformation

3. **Application 1: Image Data Compression Using PCA**
    - Import Libraries
    - Upload Image from device (any image)
    - Converting Image to Grayscale Image
    - Perform PCA on the image using sklearn.decomposition 
    - Reconstruction of the grayscale image by initialising Incremental PCA 
    - Reconstruct and plot image for a given number of components

4. **Application 2: Noise Reduction Using PCA**
    - Load Data from sklearn.datasets
    - Plotting the Scatter Plot
    - Visualizing Data Without Noise
    - Generate noisy versions of digit images by adding normal distributed noise
    - Filtering Data Without Noise

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
   - Import all libraries required. 

4. **Run Application 1: Image Data Compression Using PCA** 
    - Upload any image in the required section: 
        - If the program is being run in Google Colab Notebook, use the first method and comment the second method. 
        - If the program is being run in any editor or notebook, use the second method and comment the first method. Change the path of the image. 
    - Read through the code and comments in the notebooks to understand the concepts and implementations.
    - Observe how the data reduction is being performed on the image using the PCA. 

5. **Run Application 2: Noise Reduction Using PCA** 
    - Read through the code and comments in the notebooks to understand the concepts and implementations.
    - Observe and understand the differences between the visualized data with and without noise. 

## Dependencies

Ensure you have the following Python libraries installed:
- pandas
- matplotlib
- numpy
- scikit-learn
- PIL
- google.colab

## Conclusion

This repository serves as an in-depth exploration of Principal Component Analysis (PCA) applied to real-world datasets, showcasing its practical applications. Through this README file, users gain a clear understanding of the repository's contents and insights into the discussed clustering methods. Utilize the provided materials to learn, experiment, and gain practical experience with PCA and its applications in data analysis and dimensionality reduction.