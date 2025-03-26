# Customer Segmentation & Interpretability Project

This project focuses on unsupervised clustering of credit card users based on behavioral and demographic data. The goal is to identify distinct customer segments and generate interpretable insights that can guide targeted marketing and product decisions.

---

## 🔍 Project Overview

- **Objective**: Segment users into meaningful clusters and interpret these segments using explainable AI tools like SHAP and LIME.
- **Approach**:
  - Principal Component Analysis (PCA) for dimensionality reduction
  - KMeans clustering for segmentation
  - SHAP and LIME for model interpretation
  - Visualizations in 2D and 3D to highlight separability

---

## 📁 Project Structure

```bash
customer-segmentation/
├── data/                    # Dataset used for clustering
├── clustering.ipynb        # Jupyter notebook with full analysis
├── models/                 # Saved clustering models (optional)
└── images/                 # Visual assets (PCA plots, SHAP, LIME outputs)
```

---

## 🧠 Techniques Used

- **Clustering**: KMeans (3 clusters)
- **Dimensionality Reduction**: PCA (2D and 3D visualizations)
- **Model Explainability**:
  - **SHAP**: Global feature importance (Shapley values)
  - **LIME**: Local instance-level interpretability

---

## 📊 Cluster Characteristics & Insights

### Cluster 0 – Moderate Utilization, Balanced Transactions
- Typical user with stable behavior
- **Opportunity**: Upsell mid-tier products or services

### Cluster 1 – Budget-Conscious, Low Credit Usage
- Lower limit and cautious usage patterns
- **Strategy**: Focus on low-cost retention strategies (e.g. cashback, low-fee plans)

### Cluster 2 – High-Value Customers, Premium Behavior
- Higher limit, consistent payments, and active usage
- **Strategy**: Promote premium services and loyalty programs

---

## 📌 Key Visualizations

- ✅ **2D PCA Plot**: Clear cluster boundaries for business interpretation
- ✅ **3D PCA Plot**: Offers deeper dimensional insight
- ✅ **SHAP Summary Plot**: Features like Education Level and Gender are critical in distinguishing clusters
- ✅ **LIME Local Explanations**: Granular view of what drives a single user’s cluster assignment

![PCA Clustering](./images/pca_clusters.png)

---

## 📈 Tools & Libraries

- `sklearn` (PCA, KMeans)
- `shap`, `lime`
- `matplotlib`, `seaborn`, `plotly`
- `pandas`, `numpy`

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open and run the notebook:
```bash
jupyter notebook Clustering_Group_Assignment.ipynb
```

---

## 🤝 Contributions
Contributions and feedback are welcome! Please open an issue or submit a pull request.

---

## 📬 Contact
Prateek Bablani  
[LinkedIn](https://www.linkedin.com/in/prateek-bablani-10222116b/)  
Email: prateek.bablani@gmail.com
