# Unsupervised clustering: K-means and Spectral clustering

This README document provides detailed information about the Data Clustering and Visualization Toolkit, a Python-based software tool designed for advanced data analysis. It leverages several libraries and techniques to perform tasks such as clustering, principal component analysis (PCA), and t-Distributed Stochastic Neighbor Embedding (t-SNE) for insights into high-dimensional data.

### Features
- Data Preprocessing: Includes log transformation and MinMax scaling.
- Clustering Algorithms: Utilizes KMeans and Spectral Clustering.
- Principal Component Analysis (PCA): Reduces dimensionality of the data.
- t-SNE Visualization: For visualizing high-dimensional data in a lower-dimensional space.
- Silhouette Score Analysis: Evaluates the quality of clustering.
- Grid Search for Hyperparameter Tuning: Optimizes parameters for KMeans clustering.
- Multiple Visualization Techniques: Scatter plots for clusters and PCA results.
- 
### Requirements
This toolkit requires the following Python libraries:

- yaml
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- sklearn
  
Ensure that these packages are installed in your Python environment. 

### Installation
- Clone the repository or download the source code.
- Install the required packages as mentioned above.
- Ensure you have the config.yaml file in your project directory with appropriate settings.
- 
### Usage
Configuration

Edit the config.yaml file to specify the path of your dataset under liver_data.

Running the Toolkit

1. Data Loading and Preprocessing:
Load data, preprocess it using log transformation and MinMax scaling.

2. Clustering and PCA:
Apply KMeans and Spectral Clustering algorithms, and perform PCA for dimensionality reduction.

3. Visualization:
Utilize various plotting functions provided in the toolkit to visualize clustering results and PCA analysis.

4. Model Evaluation:
Use silhouette scores to evaluate the performance of the clustering models.
