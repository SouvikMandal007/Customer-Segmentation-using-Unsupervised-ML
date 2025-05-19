# Customer Segmentation using Unsupervised ML

This project demonstrates customer segmentation using unsupervised learning (KMeans & T-SNE) in Python.

---

## 📂 Dataset

* **File**: `new.csv`
* **Rows**: 2,240 → 2,216 (after cleaning)
* **Columns**: 29 (reduced post-cleaning)

---

## 🛠️ Tools & Libraries

* Python, Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (KMeans, T-SNE, LabelEncoder, StandardScaler)

---

## 🚀 Workflow

1. **Import Libraries & Load Data**
2. **Data Cleaning**

   * Drop nulls, irrelevant columns
   * Extract date components
3. **EDA & Visualization**

   * Count plots, correlation heatmap
4. **Encoding & Scaling**

   * Label encode categorical features
   * Scale using `StandardScaler`
5. **Dimensionality Reduction**

   * T-SNE for 2D visualization
6. **Clustering**

   * Elbow method → optimal `k=5`
   * KMeans for segmentation
   * Visualize clusters

---

## 🔍 Outcome

* Identified 5 distinct customer segments
* Enables targeted marketing and personalization

---

## 📁 Structure

```
customer-segmentation/
├── new.csv
├── customer_segmentation.ipynb
├── README.md
```

---

## 📬 Contact

* GitHub: [SouvikMandal007](https://github.com/SouvikMandal007)
* Email: [souvikmandal0321@gmail.com](mailto:souvikmandal0321@gmail.com)
