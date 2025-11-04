**🛍️ ShopSense: Mall Customer Segmentation Using Machine Learning**

**🔍 Data-Driven Insights into Customer Behavior**

**📖 Project Overview:-**

ShopSense is an unsupervised machine learning project that segments mall customers based on their demographics and spending behavior.
Using clustering techniques like KMeans and Agglomerative Clustering, this project identifies distinct customer groups to help businesses design personalized marketing strategies, improve customer retention, and optimize sales performance.

**💼 Business Problem:-**
Mall management currently treats all customers equally, leading to inefficient marketing campaigns and missed sales opportunities.
The goal is to leverage data to understand:

1. Which customers spend more,
2. Which are budget-conscious,
3. And how demographics affect spending behavior.

By identifying these segments, the business can target each group effectively with the right offers and services.

**🎯 Objectives:**

1. Perform Exploratory Data Analysis (EDA) to understand patterns in customer demographics and spending.
2. Engineer useful features such as Age Groups and Income Brackets.
3. Build preprocessing pipelines using ColumnTransformer and StandardScaler.
4. Apply KMeans and Agglomerative Clustering for segmentation.
5. Visualize results using PCA (2D) and interpret the clusters.
6. Save trained models for future predictions.

**🧠 Technologies & Libraries Used**

1. Python 3.x
2. Pandas, NumPy
3. Matplotlib, Seaborn
4. Scikit-learn
5. Joblib
6. Jupyter Notebook

**Dataset Information**

Dataset: [Mall Customer Segmentation Data (Kaggle)](https://www.kaggle.com/datasets/shwetabh123/mall-customers)

Description: The dataset contains demographic and spending information for mall customers.

**⚙️ Project Workflow**

1. Data Loading & Cleaning:-Remove irrelevant columns (CustomerID), Handle missing values.
2. Exploratory Data Analysis (EDA):- Visualize distributions, correlations, and relationships
3. Feature Engineering:- Create Age_group and Income_bracket features, Encode categorical columns.
4. Preprocessing Pipeline:- Build scalable pipeline using ColumnTransformer
5. Dimensionality Reduction:-Apply PCA (2 components) for 2D visualization
6. Modeling & Clustering:- KMeans Clustering, Agglomerative (Hierarchical) Clustering
7. Model Saving:- Save pipelines using joblib for reuse

**📊 Results**

1. KMeans and Agglomerative Clustering both identified 5 meaningful customer segments.
2. PCA visualization showed clear cluster boundaries indicating distinct customer behavior.
3. Each cluster represents unique shopper personas like:
   1. High-income, low-spending professionals
   2. Young high spenders
   3. Middle-income moderate buyers

**Conclusion:-**

In conclusion, the ShopSense: Mall Customer Segmentation project successfully demonstrates how unsupervised machine learning can be applied to understand customer behavior and purchasing patterns. By using algorithms like KMeans and Agglomerative Clustering, we identified distinct customer groups based on demographics, income, and spending scores. These clusters reveal valuable insights—such as high-income low-spending customers, young high spenders, and moderate-income average buyers—which can help businesses design more personalized marketing campaigns, improve customer engagement, and increase overall profitability. Through effective preprocessing, feature engineering, and visualization using PCA, the project showcases a complete end-to-end ML workflow that transforms raw customer data into actionable business intelligence.

**📈 Future Improvements**

1. Add DBSCAN for density-based clustering
2. Integrate with a Streamlit Dashboard for interactive visualization
3. Deploy as a customer segmentation API for marketing teams

**👤Author:- Om Patil**

📧 Data Science & Machine Learning Enthusiast

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)

👨‍💻GitHub Profile: [Om Patil](https://github.com/OmPatil2806) 
