# PCA Project for Handwritten Digit Recognition

This project demonstrates the use of **Principal Component Analysis (PCA)** for dimensionality reduction on a dataset of handwritten digits, aiming to improve computational efficiency while retaining key characteristics of the data. Below is a summary of the key objectives, approach, and findings from the project.

## Project Overview
- **Objective**: To apply PCA on a dataset of handwritten digits to reduce dimensionality and determine the separability of different digit classes.

## Approach
- **Dataset**: Handwritten digit images in an 8x8 pixel format, where each pixel represents grayscale intensity.
- **Data Preprocessing**:
  - Loaded the dataset and visualized digit samples.
  - Standardized the data using **StandardScaler** to ensure that PCA could capture the principal components effectively.
- **PCA Application**:
  - Implemented PCA to reduce the 64-dimensional pixel data to a lower dimension while retaining maximum variance.
  - Analyzed the explained variance ratio to identify optimal component count.
- **Visualization**: 
  - Plotted PCA-transformed data in 2D to observe digit clustering and separability.

## Results
- **Explained Variance**: Initial 2D PCA explained around 21% of the variance; further components were suggested for more informative clustering.
- **Clustering Observation**: Visualized clustering for two principal components, showing partial separability among digit classes.

## Key Insights
- **Dimensionality Reduction**: PCA successfully reduced dimensions, providing a manageable dataset size for further analysis or modeling.
- **Digit Separability**: Despite reducing dimensions, some digit classes were visually separable, indicating PCA’s effectiveness in retaining core data patterns.

## How to Run
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Use `pip install -r requirements.txt` to install necessary libraries.
3. **Run the Notebook**: Open the Jupyter Notebook and execute cells to preprocess the data, apply PCA, and visualize the results.
