# Customer Segmentation & Churn Prediction

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.2-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
This repository contains two integrated projects focused on **customer analytics** in the telecom sector:

1. **Customer Segmentation (Unsupervised Learning)**
   - Applied **K-Means clustering** with PCA visualization to segment customers.
   - Identified customer groups to guide targeted marketing strategies.

2. **Churn Prediction (Supervised Learning)**
   - Built **Logistic Regression** and **Random Forest** classifiers to predict churn.
   - Evaluated using **classification reports, confusion matrices, ROC curves, and SHAP explainability**.

These projects showcase the **end-to-end data science workflow**, from preprocessing → modeling → interpretability → business insights.

---

## 📂 Repository Structure

```
Customer-Segmentation-Churn-Prediction/
│── README.md
│── requirements.txt
│── LICENSE
│── Customer Segmentation & Churn Prediction.pptx   # presentation
│
├── notebooks/
│   ├── segmentation_notebook.ipynb
│   └── churn_notebook.ipynb
│
├── images/
│   ├── segmentation/
│   │   ├── clusters_scatter.png
│   │   └── shap_summary.png
│   │
│   └── churn/
│       ├── rf_confusion_matrix.png
│       ├── logreg_roc_curve.png
│       └── shap_force.png
│
├── reports/
│   ├── Logistic_Regression_classification_report.csv
│   └── Random_Forest_classification_report.csv
│
└── data/   (optional if dataset is small, otherwise link to Kaggle)
```

---

## 📊 Key Visuals

### 🔹 Customer Segmentation (K-Means Clustering)
![Segmentation Clusters](images/segmentation/clusters_scatter.png)

### 🔹 Churn Prediction – Random Forest Confusion Matrix
![Random Forest Confusion Matrix](images/churn/rf_confusion_matrix.png)

### 🔹 Churn Prediction – SHAP Feature Importance
![SHAP Summary](images/churn/shap_summary.png)

👉 More visuals are available in the [`/images`](./images) folder.

---

## 🛠 Tech Stack
- Python 3.9  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn (Logistic Regression, Random Forest, K-Means)  
- SHAP (model explainability)  

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/Customer-Segmentation-Churn-Prediction.git
   cd Customer-Segmentation-Churn-Prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebooks inside the `/notebooks` folder:
   ```bash
   jupyter notebook
   ```

---

## 📑 Results & Insights
- **Segmentation**: Identified 4 distinct customer clusters with clear behavioral differences.  
- **Churn Prediction**:  
  - Logistic Regression → simple, interpretable baseline.  
  - Random Forest → higher accuracy and better recall for churners.  
  - SHAP analysis → key drivers of churn included **tenure, contract type, and monthly charges**.  

📌 See the full **presentation**: [Customer Segmentation & Churn Prediction.pptx](./Customer%20Segmentation%20%26%20Churn%20Prediction.pptx)

---

## 📜 License
This project is licensed under the terms of the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.
