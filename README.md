
# Iris Flower Classification 🌸

This is a beginner-friendly machine learning project to classify iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — using popular classification algorithms.

## 📊 Dataset Description

The dataset used is the classic **Iris Dataset**, available in Scikit-learn. It includes **150 samples** with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Each instance is labeled with one of the three species.

## 🔧 Preprocessing & Model Training

### Data Preprocessing:
- Loaded using Scikit-learn or Pandas
- Checked for missing values (none found)
- Normalized/Standardized features (if needed)
- Split data into **80% training** and **20% testing**

### Model Training:
- Models Used:
  - **K-Nearest Neighbors (KNN)**
  - **Decision Tree Classifier**
  - **Logistic Regression**
- Hyperparameter tuning performed (e.g., `n_neighbors` for KNN)

## 📈 Evaluation Results

- Evaluation Metrics: **Accuracy**, **Precision**, **Recall**, **F1-score**
- Visualizations:
  - Confusion Matrix (via Seaborn heatmap)
  - Scatter plots for feature separability

**Example Accuracy:** ~97% using Decision Tree or KNN

## 💻 Installation Instructions

### Required Libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### To Run the Project:
1. Clone or download the repository
2. Open `iris_flower_classification.ipynb` in Jupyter or Google Colab
3. Run all cells to see results and visualizations

---

## 🙋‍♀️ Submitted by
**Amruthavarshini Karri**
