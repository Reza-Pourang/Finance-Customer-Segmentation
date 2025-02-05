# Finance-Customer-Segmentation

## Project Overview
This project focuses on **customer segmentation** in the financial sector using **machine learning clustering techniques**. The dataset is derived from a Portuguese banking institution’s direct marketing campaign, where customers were contacted via phone to subscribe to term deposits. The goal is to analyze segmentation patterns and build a predictive model for classifying new customers.

## Research Questions
- How can demographic and financial behavior data improve customer segmentation?
- What features have the most impact on customer segmentation?
- How do different clustering algorithms affect segment stability?
- Can a predictive model effectively assign new customers to predefined segments?

## Objectives
- **Data Preprocessing & Feature Engineering**: Cleaning, encoding, and scaling dataset features.
- **Clustering Analysis**: Implementing K-Means, DBSCAN, and GMM for segmentation.
- **Robustness & Stability Testing**: Evaluating segmentation reliability.
- **Predictive Modeling**: Training a **Random Forest Classifier** to predict customer segments.
- **Business Insights**: Extracting valuable marketing strategies from customer segments.


## Methodology
### 1️⃣ Data Preprocessing
- Handling missing values & encoding categorical variables.
- Scaling numerical features & feature engineering.

### 2️⃣ Clustering Analysis
- **K-Means**: Determining the optimal number of clusters.
- **DBSCAN**: Identifying dense customer segments.
- **GMM**: Modeling complex distributions for better segmentation.

### 3️⃣ Predictive Modeling
- Training a **Random Forest Classifier** for real-time customer classification.
- Evaluating model performance with Precision, Recall, and F1-score.

### 4️⃣ Business Insights
- Identifying **high-balance customers** for premium financial products.
- Recognizing **frequent campaign contacts** to improve engagement strategies.

## Key Findings
- **GMM provided the best clustering performance** with a high silhouette score.
- **High-balance customers** were younger, highly educated, and had minimal loan engagement.
- **Frequent campaign contacts** had lower savings and high housing loan rates.
- **The predictive model achieved near-perfect accuracy** in segment assignment.

