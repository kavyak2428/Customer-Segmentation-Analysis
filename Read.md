# **Customer Segmentation Project Report**  

## **1. Project Overview**  
Customer segmentation is a technique used to divide customers into distinct groups based on their purchasing behavior, income, and engagement with a business. The goal of this project is to analyze customer data, identify patterns, and provide insights for better decision-making in marketing strategies.  

---

## **2. Project Requirements**  

### **2.1 Hardware Requirements**  
- **Processor:** Intel Core i5 or higher  
- **RAM:** Minimum 8GB (16GB recommended for larger datasets)  
- **Storage:** At least 10GB free space  
- **GPU:** Not required but can enhance visualization processing  

### **2.2 Software Requirements**  
- **Operating System:** Windows / Linux / macOS  
- **Programming Language:** Python (version 3.8 or higher)  
- **Libraries Used:**
  - `pandas` – for data manipulation  
  - `numpy` – for numerical operations  
  - `matplotlib` & `seaborn` – for data visualization  
  - `scikit-learn` – for machine learning (KMeans, PCA, StandardScaler)  

- **Development Environment:** Jupyter Notebook / VS Code / PyCharm  

---

## **3. Data Collection & Processing**  
- **Dataset Used:** `ifood_df.csv` (Customer transaction data)  
- **Features Selected for Clustering:**
  - **Income** (Customer’s annual income)  
  - **Spending behavior** (Purchases across different product categories)  
  - **Engagement Metrics** (Web visits, store purchases, recency of last purchase)  

- **Preprocessing Steps:**
  - Checking for missing values  
  - Standardizing numerical data using `StandardScaler`  
  - Feature selection for clustering  

---

## **4. Machine Learning Model Used**  
### **4.1 Clustering Algorithm: K-Means**  
- **Why K-Means?**  
  - Efficient for large datasets  
  - Finds customer segments based on spending patterns  

- **Hyperparameter Selection:**  
  - **Optimal K**: Determined using the **Elbow Method**  
  - **Final K Value Chosen:** 4 clusters  

- **Cluster Interpretation:**  
  - **Cluster 0:** High-income, high spenders (Target premium services)  
  - **Cluster 1:** Moderate-income, mid-level spenders (Offer personalized discounts)  
  - **Cluster 2:** Low-income, low spenders (Introduce budget-friendly options)  
  - **Cluster 3:** Online-oriented customers (Enhance digital marketing)  

---

## **5. Data Visualization & Interpretation**  
- **PCA (Principal Component Analysis)** was used to reduce dimensionality for visualization.  
- **Scatter Plot:** Used to visualize clusters in 2D space.  
- **Bar Chart:** Displays average spending across clusters.  

---

## **6. Business Insights & Recommendations**  
- **High spenders (Cluster 0):** Provide exclusive membership plans.  
- **Moderate spenders (Cluster 1):** Target with special discount offers.  
- **Low spenders (Cluster 2):** Bundle low-cost products to increase purchases.  
- **Online-oriented customers (Cluster 3):** Focus on improving digital experience & targeted ads.  

---

## **7. Challenges Faced & Solutions**  
| Challenge | Solution |
|-----------|----------|
| Missing values in dataset | Data cleaning and imputation |
| Selecting the right number of clusters | Used **Elbow Method** to determine K |
| Uneven distribution of data | Standardized data to ensure fair clustering |
| Performance issues in visualization | Sampled data for scatter plots |

---

## **8. Conclusion**  
This project successfully segmented customers based on purchasing behavior and income, allowing businesses to optimize their marketing strategies. Using **K-Means clustering and PCA visualization**, we provided actionable insights that can drive targeted marketing and improve customer retention.  

---

## **9. Future Improvements**  
- Use **Hierarchical Clustering** for better interpretability.  
- Implement **DBSCAN** to detect anomalies in customer behavior.  
- Incorporate **demographic data** (age, location) for better segmentation.  
- Automate insights generation using **Power BI dashboards**.  

