# MLPR-Lab5
This lab focuses on applying machine learning and pattern recognition techniques using Python in a Jupyter Notebook environment. The main objective is to explore distance-based classification and clustering methods, perform feature extraction, visualize results, and analyze model performance using appropriate evaluation techniques.

Aim of the Lab
1) Implement image-based feature extraction using HSV color space.
2) Apply clustering (K-Means) for grouping similar facial features.
3) Visualize clustering results using scatter plots and image annotations.
4) Understand distance metrics used in classification algorithms.
5) Analyze model performance concepts such as bias, variance, and cross-validation.

Methodology
The following steps were followed:
1) Data Preparation
2) Load images and detect faces using OpenCV.
3) Extract face regions from images.
4) Feature Extraction
5) Convert images from BGR to HSV color space.
6) Compute average Hue and Saturation values for each detected face.

Clustering
Apply K-Means clustering to group faces based on extracted features.
Predict cluster membership for template images.

Visualization
Plot clusters using scatter plots.
Display face thumbnails as points on the graph.
Mark cluster centroids and template image positions.

Analysis
Compare distance metrics.
Discuss real-world applications of distance-based algorithms.
Explain cross-validation, bias, and variance in KNN.

Key Findings
HSV color features can effectively separate visually similar face groups.
K-Means clustering successfully identifies natural groupings in the feature space.
Visualization improves understanding of model behavior and cluster separation.
Choice of distance metric significantly impacts classification performance.
Cross-validation provides a more reliable estimate of model generalization.

Results & Visualizations
The notebook includes:
1) Cluster scatter plots (Hue vs Saturation)
2) Face image annotations within clusters
3) Centroid visualization
4) Template image cluster prediction
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/31507e0f-cb20-45a4-9e22-c7dec9cf482d" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/53a2a85b-a3e0-4721-82e2-a66d4b3fbe6f" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/5adeecc8-7556-47df-a0c7-93464653616d" />
<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/bd03c3c7-21e0-48c1-bd0d-150addfe8a38" />

Concepts Covered
1) Distance Metrics (Euclidean, Manhattan, Chebyshev, Minkowski, etc.)
2) K-Means Clustering
3) K-Nearest Neighbors (KNN)
4) Bias–Variance Tradeoff
5) Cross Validation
6) Feature Engineering using Color Spaces

Technologies Used: 
Python,
Jupyter Notebook,
OpenCV,
NumPy,
Matplotlib,
Scikit-learn
