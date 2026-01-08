![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Clustering](https://img.shields.io/badge/Model-KMeans-informational)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

# Kmeans_Clustering-on-School_data
This project applies K-Means clustering to group schools based on infrastructure, student–teacher ratio, classrooms, and a Digital Readiness Index (DRI). The model identifies distinct school clusters to support data-driven planning, resource allocation, and Digital Twin–based educational insights.

# Objectives
1. Group schools based on similarity in infrastructure and academic capacity
2. Construct a Digital Readiness Index (DRI) from multiple infrastructure features
3. Identify meaningful school clusters for policy-level insights
4. Enable Digital Twin–based analysis and future simulations

# Dataset Description
# The dataset contains school-level information including:
1. Number of students
2. Student–Teacher Ratio (STR)
3. Number of classrooms
4. Digital infrastructure indicators (electricity, internet, smart classrooms, transport)
5. Latitude and longitude (used only for visualization)

# Methodology
1. Data Preprocessing
 - Handling missing values
 - Feature transformation
 - Construction of Digital Readiness Index (DRI)

2. Feature Scaling
 - Min-Max Scaling applied to ensure equal contribution of features

3. Clustering
 - K-Means algorithm implemented using Scikit-learn
 - Optimal number of clusters selected using the Elbow Method (K = 4)

4. Post-Cluster Analysis
 - Cluster-wise statistical analysis (mean, median, standard deviation)
 - Cluster interpretation and labeling

5. Visualization
 - Scatter plots and box plots
 - Geographic cluster visualization using Folium (post-clustering)

# Results
1. Schools were grouped into four distinct clusters
2. Each cluster represents a different level of infrastructure and digital readiness
3. Clusters are interpretable and suitable for planning and intervention analysis
4. K-Means outperformed DBSCAN for this dataset due to better stability and clarity

# Technologies Used
1. Programming Language: Python
2. Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Folium
3. Tools: Jupyter Notebook, VS Code
4. Version Control: Git

# Project Structure
EduTwin-KMeans/
│
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks
├── visuals/            # Plots and maps
├── src/                # Source code
├── README.md           # Project documentation

# Challenges & Limitations
1. Sensitivity of K-Means to feature scaling
2. Limited accuracy of some real-world data points
3. Spatial data not suitable for direct clustering

# Author
Dhananjay Rupesh More
MCA Student | Data Analytics & Machine Learning
Focused on data-driven solutions for real-world problems

