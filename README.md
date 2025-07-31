## City Happiness Clustering

City Happiness Clustering is a machine learning project that groups cities based on their happiness index and related socio-environmental factors. The project uses both K-Means and Hierarchical Clustering to uncover patterns and similarities between cities.

## Project Objectives
- Cluster cities based on happiness index and influencing factors.
- Compare K-Means and Hierarchical Clustering performance.
- Visualize cluster patterns and analyze key insights from grouped data.
- Build a reproducible workflow from data preprocessing to cluster evaluation.

## Dataset
- **File:** `city_happinessIndex.csv`
- **Description:** Contains features such as air quality, cost of living, healthcare quality, environmental cleanliness, and traffic density.
- **Target:** Unsupervised learning project.
- **Goal:** Discover natural clusters of cities with similar happiness patterns.

## Clustering Models Used
- K-Means (with Elbow Method to find optimal clusters)
- Hierarchical Clustering (Ward linkage & dendrogram visualization)

## Tools & Libraries
- pandas
- NumPy
- matplotlib
- scikit-learn
- scipy

## Workflow
1. Data Cleaning & Preprocessing
2. OneHotEncoding & Standardization
3. Dimensionality Reduction with PCA
4. Clustering with K-Means & Hierarchical
5. Visualization of Clusters and Dendrograms

## Results
- Hierarchical Clustering achieved a silhouette score of **0.67**.
- K-Means achieved a silhouette score of **0.56**.
- Optimal number of clusters determined using Elbow Method and dendrogram analysis.