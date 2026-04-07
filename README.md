# Mall Customer Segmentation (End-to-End Data Science Project)

## 📌 Project Overview
This project performs customer segmentation using unsupervised learning techniques. The goal is to group customers based on their behavior for better business understanding and targeted marketing.

---

## 🎯 Objective
- Identify distinct customer segments
- Reduce data dimensionality using PCA
- Apply KMeans clustering
- Evaluate clustering performance using Silhouette Score

---

## 📂 Dataset
- Mall Customers Dataset
- Features include:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

---

## ⚙️ Steps Performed

### 1. Data Preprocessing
- Selected numerical features
- Standardized the data using StandardScaler

### 2. Dimensionality Reduction
- Applied PCA to reduce features to 2 components
- Helps in visualization and noise reduction

### 3. Clustering (KMeans)
- Applied KMeans algorithm
- Used Elbow Method to estimate optimal clusters

### 4. Model Evaluation
- Used Silhouette Score to evaluate cluster quality
- Higher score indicates better-defined clusters

---

## 📊 Results
- Customers segmented into distinct groups
- PCA enabled better visualization
- Silhouette Score validated clustering performance

---

## 💡 Key Insights
- Different customer groups show different spending behaviors
- Businesses can target high-value customers more effectively
- Helps in personalized marketing strategies

---

## 🚀 How to Run
1. Open the Jupyter Notebook
2. Run all cells step-by-step
3. Ensure dataset file is in the same directory

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📌 Future Improvements
- Add cluster profiling (business interpretation)
- Use advanced clustering (DBSCAN, Hierarchical)
- Deploy as a web app

---

## 👨‍💻 Author
Praveen Kumar
