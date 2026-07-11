# 📈 AI-Driven Marketing Campaign Analysis

This project leverages machine learning and data analytics to evaluate and optimize marketing campaign performance. It includes data preprocessing, segmentation, predictive modeling, and feature importance analysis — all focused on understanding and improving lead conversion and ROI.

## 🚀 Project Overview

The goal of this project is to:
- Clean and preprocess marketing campaign data
- Segment audiences using clustering (KMeans)
- Predict lead conversion using a Random Forest classifier
- Identify key features driving conversions
- Visualize campaign performance metrics for strategic insights

## 🧠 Techniques Used

| Category | Techniques/Tools |
|----------|------------------|
| Data Cleaning | Pandas, Regex, Type Conversion |
| Feature Engineering | Age Range Extraction, One-Hot Encoding |
| Visualization | Seaborn, Matplotlib |
| Supervised Learning | Random Forest Classifier |
| Unsupervised Learning | KMeans Clustering, PCA (optional) |
| Model Evaluation | Accuracy, Precision, Recall, F1 Score |
| Scaling | StandardScaler |

## Key Features
1. Conversion Rate Analysis: Visual distribution and threshold setting

2. Clustering: Segment campaigns into behaviorally distinct groups

3. Lead Conversion Prediction: Trained Random Forest classifier

4. Feature Importance: Determine what influences conversion most

5. Performance Metrics: Evaluate model accuracy, recall, F1, etc.

## Insights
1.  Tailored Campaign Strategies
   Each cluster reveals a common pattern that helps you design personalized marketing strategies:

     Cluster 1 (High Conversion Rate, Low Duration, "All Ages", "Influencer"):
     → Short campaigns using influencers work well across all ages.
     → Ideal for broad, fast-response promotions.

     Cluster 3 (High ROI and High Conversion Rate, "Men 25-34", "Search"):
     → Search ads targeted at this group are very efficient.
     → Scale this segment for performance.

     Cluster 0 (Low conversion and ROI, "Men 18-24", "Email"):
     → Email might not be effective for this segment — consider testing new channels.


2. Channel Optimization
   Influencer campaigns (Clusters 1 & 4) yield high conversion rates but differ in ROI and duration — suggesting different audience-channel fit.

   Search campaigns seem effective across clusters — particularly for Men 25-34 and Women 25-34.


3. If the goal is ROI:
   Prioritize clusters like Cluster 2 (Women 25–34, Search) and Cluster 5 (Men 25–34, Email) with ROI above 6.

   If the goal is high conversion:
   Focus on Cluster 4 and Cluster 6.


4. Men 18-24 + Influencer (Cluster 4) performs better than Men 18-24 + Email (Cluster 0).
   Try moving more budget from email to influencer for this group.
     

5. Acquisition Cost and impressions are major factors in lead conversion.

6. Clustering revealed distinct cost-performance groupings, helping identify underperforming segments.


