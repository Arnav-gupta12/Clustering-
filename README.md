# Clustering


# Clustering Analysis on Iris Dataset

This project demonstrates a comparative study of clustering techniques on the Iris dataset using different data preprocessing techniques.

---

## 📊 Dataset
**Dataset Name**: Iris  
**Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/iris)  
**Attributes**:  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  
- Class (Iris-setosa, versicolor, virginica)

---

## 🧠 Clustering Techniques Used

- **KMeans Clustering**
- **Hierarchical Clustering** (Agglomerative)
- **Mean Shift Clustering**

---

## 🔁 Preprocessing Techniques

- **None (Raw Data)**
- **Normalization** (`StandardScaler`)
- **PCA** (Principal Component Analysis)
- **Normalization + PCA**

---

## 🧪 Evaluation Metrics

| Metric                | Description |
|------------------------|-------------|
| Silhouette Score       | Measures how well samples are clustered |
| Calinski-Harabasz Index | Higher means better-defined clusters |
| Davies-Bouldin Score   | Lower values indicate better clustering |

---

## 📈 Visualizations

The following graphs are plotted to compare clustering performance:
- Silhouette Score
- Calinski-Harabasz Score
- Davies-Bouldin Score

---

## ✅ Results Summary

- **KMeans with Normalization and PCA** gave the best performance in terms of Silhouette and Calinski-Harabasz scores.
- **Mean Shift** works well when combined with Normalization, but less effective with PCA.
- **Hierarchical Clustering** showed stable but slightly lower scores than KMeans.
- **Preprocessing** significantly improves clustering quality.

---

## 📂 Files

- `iris_clustering_analysis.ipynb`: Colab Notebook for complete analysis
- `README.md`: This file

---

## 🚀 How to Run

1. Open the `iris_clustering_analysis.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Run all cells to perform clustering and view evaluation.
3. Check graphs and result table.
4. Modify cluster values or preprocessing techniques to explore further!

---

## 📬 Conclusion

This experiment validates that:
- Clustering performance is highly influenced by preprocessing.
- KMeans performs best on this dataset.
- Evaluation using multiple metrics provides better judgment.

---

