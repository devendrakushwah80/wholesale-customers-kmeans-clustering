# Wholesale Customers Segmentation using K-Means Clustering

## 📌 Project Overview
This project applies **K-Means clustering** to the Wholesale Customers dataset to segment customers based on their annual spending across different product categories.  
The goal is to identify meaningful customer groups that can help businesses understand buying behavior.

---

## 📂 Dataset Information
**Dataset:** Wholesale Customers Data (UCI Machine Learning Repository)

### Features:
- Channel (categorical)
- Region (categorical)
- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

---

## 🎯 Objective
- Perform customer segmentation using **unsupervised learning**
- Find the optimal number of clusters using the **Elbow Method**
- Analyze and interpret customer clusters

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow
1. Load and inspect dataset
2. Data preprocessing
   - Drop categorical columns (Channel, Region)
   - Feature scaling using StandardScaler
3. Apply **Elbow Method** to determine optimal K
4. Train **K-Means clustering model**
5. Assign cluster labels to customers
6. Analyze clusters using mean feature values
7. Visualize clusters using **PCA**
8. Save final clustered dataset

---

## 📉 Elbow Method
The Elbow Method is used to determine the optimal number of clusters by plotting WCSS against different K values.  
The point where the curve bends indicates the best K.

---

## 📊 Cluster Interpretation
Each cluster represents a unique customer segment:
- High grocery & detergent buyers
- Fresh product–focused customers
- Mixed or low-volume buyers

These insights can be used for:
- Targeted marketing
- Inventory planning
- Customer profiling

---

## 📈 Visualization
- PCA is used to reduce dimensions
- 2D scatter plot helps visualize cluster separation

---

## 📁 Files in Repository
├── Kmeans_clustering_elbow.ipynb
├── wholesale_customers_with_clusters.csv
├── requirements.txt
└── README.md

---

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/your-username/wholesale-customers-kmeans-clustering.git
```

Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook


Run Kmeans_clustering_elbow.ipynb

📌 Future Improvements

Add Silhouette Score comparison

Try Hierarchical Clustering

Perform RFM analysis

Deploy clustering as a web app

👤 Author

Devendra Kushwah
