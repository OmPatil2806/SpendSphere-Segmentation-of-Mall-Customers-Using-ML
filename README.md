# 🛍️ ShopSense: Mall Customer Segmentation Using Machine Learning

## 🔍 Data-Driven Insights into Customer Behavior

---

## 📖 Project Overview

**ShopSense** is an **unsupervised machine learning project** focused on segmenting mall customers based on their **demographics and spending patterns**.  
By leveraging **clustering techniques** such as **KMeans** and **Agglomerative Clustering**, the project identifies distinct customer groups to help businesses create **personalized marketing strategies**, improve **customer retention**, and **optimize sales performance**.

---

## 💼 Business Problem

Mall management currently treats all customers uniformly — leading to **inefficient marketing campaigns** and **missed revenue opportunities**.  

The goal is to use **data-driven segmentation** to understand:
1. 🏦 Which customers are high spenders  
2. 💸 Which are budget-conscious  
3. 👨‍👩‍👧 How demographics affect spending behavior  

With this knowledge, businesses can **target each segment effectively** using customized offers and services.

---

## 🎯 Objectives

1. Perform **Exploratory Data Analysis (EDA)** to understand customer demographics and spending behavior  
2. Engineer new features like **Age Groups** and **Income Brackets**  
3. Build a **preprocessing pipeline** using `ColumnTransformer` and `StandardScaler`  
4. Apply **KMeans** and **Agglomerative Clustering** for segmentation  
5. Visualize clusters using **PCA (2D)** and interpret results  
6. Save trained models using **joblib** for future use  

---

## 🧠 Technologies & Libraries Used

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python 3.x |
| Data Manipulation | pandas, NumPy |
| Visualization | matplotlib, seaborn |
| Machine Learning | scikit-learn |
| Model Saving | joblib |
| Environment | Jupyter Notebook / PyCharm |

---

## 📊 Dataset Information

**Source:** [Mall Customer Segmentation Data (Kaggle)](https://www.kaggle.com/datasets/shwetabh123/mall-customers)

**Description:**  
The dataset contains **demographic and spending information** of mall customers — including **Age**, **Annual Income**, and **Spending Score** — ideal for clustering and behavioral segmentation.

---

## ⚙️ Project Workflow

1. **Data Loading & Cleaning**  
   - Remove irrelevant columns (e.g., `CustomerID`)  
   - Handle missing values if present  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize distributions and correlations  
   - Study relationships between income, age, and spending  

3. **Feature Engineering**  
   - Create `Age_Group` and `Income_Bracket`  
   - Encode categorical features (e.g., Gender)  

4. **Preprocessing Pipeline**  
   - Use `ColumnTransformer` and `StandardScaler` for scalable preprocessing  

5. **Dimensionality Reduction**  
   - Apply **PCA (2 components)** for 2D visualization of clusters  

6. **Modeling & Clustering**  
   - Apply **KMeans Clustering**  
   - Apply **Agglomerative (Hierarchical) Clustering**  

7. **Model Saving**  
   - Save trained pipelines and models using `joblib`  

---

## 📈 Results

| Model | Number of Clusters | Insights |
|--------|--------------------|-----------|
| KMeans | 5 | Clear segmentation with distinct customer groups |
| Agglomerative | 5 | Consistent cluster structure with better interpretability |

### 🧩 Key Cluster Insights
1. 💼 **High-income, low-spending professionals**  
2. 🎉 **Young, high spenders**  
3. 👨‍👩‍👧 **Middle-income, moderate buyers**

PCA visualization confirmed **clear cluster boundaries**, validating the segmentation approach.

---

## 🧾 Conclusion

**ShopSense: Mall Customer Segmentation** demonstrates the power of **unsupervised learning** in understanding customer behavior.  
Through **KMeans** and **Agglomerative Clustering**, the model identified actionable customer personas based on **income**, **age**, and **spending score**.  

These insights empower businesses to:
- Design **targeted marketing campaigns**
- Improve **customer engagement**
- Enhance **sales and profitability**

With robust **feature engineering**, **preprocessing**, and **visualization**, this project provides a **complete end-to-end ML workflow** that transforms raw data into actionable intelligence.

---

## 🔮 Future Improvements

1. 🌀 Add **DBSCAN** for density-based clustering  
2. 💻 Integrate with **Streamlit Dashboard** for interactive visualization  
3. ⚙️ Deploy as a **Customer Segmentation API** for marketing teams  

---

## 👤 Author

**Om Patil**  
📧 *Data Science & Machine Learning Enthusiast*  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
