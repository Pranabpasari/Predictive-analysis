# Hospital Performance Predictive Analysis

This project focuses on analyzing and predicting hospital performance using real-world
U.S. healthcare data published by the Centers for Medicare & Medicaid Services (CMS)
via HealthData.gov.

The objective of this project is to apply exploratory data analysis, supervised learning,
and unsupervised learning techniques to understand patterns in hospital performance and
evaluate the effectiveness of machine learning models on public healthcare data.

---

## 📊 Dataset

- **Source:** HealthData.gov (CMS – Hospital General Information)
- **Type:** Public U.S. Government Healthcare Dataset
- **Format:** CSV
- **Description:** Contains information about hospitals across the United States including
  hospital type, ownership, availability of emergency services, and overall performance
  ratings.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

1. Data Loading and Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering and Encoding  
4. Supervised Learning Models  
5. Unsupervised Learning Models  
6. Visualization of Results  
7. Performance Evaluation and Interpretation  

---

## 🤖 Machine Learning Models

### Supervised Learning
- Logistic Regression
- Decision Tree Classifier

### Unsupervised Learning
- K-Means Clustering
- Hierarchical Clustering (Dendrogram)

---

## 📈 Key Insights

- Hospital characteristics such as ownership, type, and emergency services influence
  overall hospital performance.
- Supervised models can predict high-performing and low-performing hospitals with
  reasonable performance given real-world data constraints.
- Unsupervised clustering reveals natural groupings of hospitals into low, medium,
  and high performance categories.
- Feature scaling is essential for distance-based clustering algorithms.

---

## ⚠️ Note on Model Performance

The accuracy of predictive models is moderate due to the complexity of healthcare systems
and the limited number of predictive features available in the dataset. Performance was
evaluated using appropriate metrics such as F1-score and confusion matrix rather than
accuracy alone.

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hospital-performance-predictive-analysis.git
