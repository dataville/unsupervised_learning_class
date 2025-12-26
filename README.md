# Unsupervised Learning Projects

This repository contains three data science projects demonstrating unsupervised learning techniques, including clustering, dimensionality reduction, and recommendation systems. These projects were completed as part of advanced machine learning coursework and showcase practical applications of data science in business contexts.

## Table of Contents
- [Projects Overview](#projects-overview)
- [Technologies Used](#technologies-used)
- [Project Details](#project-details)
  - [1. Wholesale Customer Segmentation](#1-wholesale-customer-segmentation)
  - [2. Restaurant Recommendation System](#2-restaurant-recommendation-system)
  - [3. Employee Retention Analysis](#3-employee-retention-analysis)
- [Key Skills Demonstrated](#key-skills-demonstrated)

## Projects Overview

| Project | Technique | Business Application | Key Outcome |
|---------|-----------|---------------------|-------------|
| Wholesale Customer Segmentation | K-Means Clustering, Hierarchical Clustering | Market segmentation for B2B wholesale distributor | Identified distinct customer segments based on purchasing patterns |
| Restaurant Recommendation System | Collaborative Filtering, Matrix Factorization | Personalized restaurant recommendations | Built recommendation engine for improved customer experience |
| Employee Retention Analysis | K-Means Clustering, PCA | HR analytics and talent retention | Segmented employees and provided actionable retention strategies |

## Technologies Used

- **Python 3.x**
- **Core Libraries:**
  - pandas - Data manipulation and analysis
  - NumPy - Numerical computing
  - scikit-learn - Machine learning algorithms
  - Matplotlib & Seaborn - Data visualization
  - scipy - Statistical analysis and hierarchical clustering

- **Machine Learning Techniques:**
  - K-Means Clustering
  - Hierarchical Clustering (Agglomerative)
  - Principal Component Analysis (PCA)
  - Collaborative Filtering
  - Standardization & Normalization
  - Silhouette Analysis
  - Elbow Method

## Project Details

### 1. Wholesale Customer Segmentation

**File:** `section05_clustering_project-working.ipynb`

**Objective:** Segment wholesale customers based on their annual spending across six product categories to enable targeted marketing strategies.

**Dataset:** Wholesale customer data containing annual spending on Fresh products, Milk, Grocery, Frozen goods, Detergents & Paper, and Delicatessen items for 440 customers.

**Methodology:**
- Data preprocessing and standardization using StandardScaler
- Exploratory data analysis to understand spending patterns
- K-Means clustering with optimal cluster determination via elbow method
- Hierarchical clustering with dendrogram visualization
- Cluster validation using silhouette scores
- Cluster profiling and interpretation

**Key Findings:**
- Successfully identified distinct customer segments based on purchasing behavior
- Different customer types show clear preferences for specific product categories
- Segments can be targeted with customized marketing and inventory strategies

**Business Impact:** Enables the wholesale distributor to develop segment-specific marketing campaigns, optimize inventory management, and improve customer relationship management.

---

### 2. Restaurant Recommendation System

**File:** `section09_recommender_project_working.ipynb`

**Objective:** Build a collaborative filtering recommendation system to suggest restaurants to users based on historical rating patterns.

**Dataset:** Restaurant ratings dataset containing 1,161 ratings from multiple consumers across various restaurants, with ratings on a 0-2 scale.

**Methodology:**
- Created user-item rating matrix with consumers as rows and restaurants as columns
- Implemented collaborative filtering approach
- Handled sparse matrix with mean imputation strategy
- Generated personalized restaurant recommendations based on user similarity
- Evaluated recommendation quality through rating predictions

**Key Findings:**
- Successfully built a recommendation engine that identifies similar users
- System can predict ratings for unvisited restaurants
- Mean-centering improves recommendation accuracy by accounting for user rating tendencies

**Business Impact:** Enhances customer experience through personalized restaurant suggestions, potentially increasing customer engagement and satisfaction.

---

### 3. Employee Retention Analysis

**File:** `section11_final_project_working.ipynb`

**Objective:** Analyze employee data to identify distinct workforce segments and develop targeted retention strategies to reduce attrition.

**Dataset:** Employee dataset including demographic information (Age, Gender), job characteristics (JobLevel, Department, MonthlyIncome, PerformanceRating, JobSatisfaction), and attrition status.

**Methodology:**
1. **Data Preparation & EDA**
   - Data cleaning and type validation
   - Exploratory analysis of employee characteristics
   - Encoding of categorical variables

2. **Initial Clustering (Round 1)**
   - K-Means clustering on raw features
   - Optimal cluster determination using elbow method and silhouette analysis
   
3. **PCA for Visualization (Round 1)**
   - Dimensionality reduction to 2D for cluster visualization
   - Assessment of explained variance

4. **Refined Clustering (Round 2)**
   - Feature standardization
   - Re-application of K-Means clustering
   - Improved cluster separation

5. **Enhanced Visualization (Round 2)**
   - PCA-based 2D visualization of refined clusters
   - Cluster interpretation and profiling

6. **Cluster Analysis & Recommendations**
   - Deep dive into each cluster's characteristics
   - Correlation of cluster membership with attrition rates
   - Development of segment-specific retention strategies

**Key Findings:**
- Identified distinct employee segments with varying attrition risks
- Uncovered relationships between job satisfaction, income, performance, and retention
- Different employee segments require tailored retention approaches

**Business Impact:** Provides HR with actionable insights to reduce turnover through targeted interventions, potentially saving significant recruitment and training costs.

---

## Key Skills Demonstrated

### Technical Skills
- **Machine Learning:** K-Means, Hierarchical Clustering, PCA, Collaborative Filtering
- **Data Analysis:** EDA, statistical analysis, pattern recognition
- **Data Preprocessing:** Standardization, normalization, encoding, missing value handling
- **Python Programming:** Efficient use of pandas, NumPy, scikit-learn
- **Visualization:** Creating insightful plots with Matplotlib and Seaborn

### Analytical Skills
- Feature selection and engineering
- Cluster validation and interpretation
- Model evaluation and optimization
- Hyperparameter tuning (determining optimal k)
- Business insight generation from technical analysis

### Domain Knowledge
- Customer segmentation strategies
- Recommendation system design
- HR analytics and workforce management
- Understanding of business metrics and KPIs


## Author

**Charles** - Data Scientist.

## License

MIT License - See LICENSE file for details.

## Acknowledgments

- Projects completed as part of Maven Data Science in Python: Unsupervised Learning coursework
