# elevate_labs-task-8
# 🛍️ Customer Segmentation using K-Means Clustering

This project applies K-Means clustering on a customer dataset to identify distinct customer groups based on spending habits, income, age, and gender.

---

## 📑 Dataset Description

| Column            | Description                            |
|-------------------|----------------------------------------|
| CustomerID        | Unique ID of the customer              |
| Gender            | Gender of the customer (Male/Female)   |
| Age               | Age of the customer                    |
| Annual Income (k$)| Customer's yearly income               |
| Spending Score    | 1–100 (higher means more spending)     |

---

## 📌 Steps Performed

### 1. Load and Visualize Dataset
- Encoded `Gender` to numeric (Male=1, Female=0)
- Scaled features for uniformity
- Applied optional **PCA** to reduce dimensions for plotting

### 2. Fit K-Means Model
- Initial clustering using `K=5`
- Assigned cluster labels

### 3. Elbow Method
- Plotted Inertia vs. K (1–10)
- Helped choose the **optimal number of clusters**

### 4. Cluster Visualization
- Used **PCA-reduced 2D data** to plot clusters
- Color-coded based on cluster labels

### 5. Clustering Evaluation
- Calculated **Silhouette Score** to evaluate the compactness and separation of clusters

---

## 🧪 Output Examples

- 📈 **Elbow Plot** for optimal K
- 🎨 **2D Scatter Plot** of clusters (PCA)
- 🧮 Silhouette Score: `e.g. 0.61`

---

## 📦 Dependencies

```bash
pip install pandas matplotlib seaborn scikit-learn
