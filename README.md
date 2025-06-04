# 🧠 Cardiotocography Analysis using Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3+-orange.svg)](https://scikit-learn.org/stable/)

This project explores the application of various machine learning classifiers to analyze **Cardiotocography (CTG)** data for improving fetal monitoring during pregnancy and labor. By automating CTG interpretation, we aim to assist healthcare professionals in making accurate, timely decisions and ultimately enhance maternal and neonatal outcomes.

---

## 📊 Project Overview

- **Domain:** Medical / Machine Learning  
- **Dataset:** [UCI Machine Learning Repository - Cardiotocography Data](https://archive.ics.uci.edu/ml/datasets/Cardiotocography)  
- **Tech Stack:** Python, NumPy, pandas, matplotlib, scikit-learn, Jupyter Notebook  
- **Classifiers Used:**  
  - Perceptron  
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - k-Nearest Neighbors (KNN)  
  - Decision Tree  

---

## 🧪 Methodology

### ⚙️ Hardware & Software

- **Processor:** AMD Ryzen 9 5900HX  
- **GPU:** NVIDIA GeForce RTX 3060  
- **RAM:** 16 GB  
- **OS:** Windows 11  
- **IDE:** Jupyter Notebook  

### 🗂️ Data Preprocessing

- 2126 labeled CTG records categorized as:  
  - **Normal (1)**  
  - **Suspect (2)**  
  - **Pathologic (3)**  
- StandardScaler used for feature scaling  
- Train-test split: 80:20  

### 📈 Model Training & Evaluation

- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score  
- Hyperparameter tuning with `GridSearchCV`  
- 5-Fold Cross-validation for robustness assessment  

---

## ✅ Results

| Classifier         | Training Accuracy | Testing Accuracy |
|--------------------|-------------------|------------------|
| Perceptron         | 89.12%            | 84.98%           |
| Logistic Regression| 90.71%            | 87.79%           |
| SVM                | 93.53%            | 90.38%           |
| KNN                | 93.18%            | 91.55%           |
| Decision Tree      | 93.82%            | 90.14%           |

- 📈 **KNN** achieved the best testing accuracy  
- 💡 **SVM** and **Decision Tree** demonstrated robust, consistent performance  
- 🔁 Cross-validation confirmed strong generalization ability  

---

## 📌 Key Takeaways

- ML models like **SVM**, **KNN**, and **Decision Tree** are well-suited for CTG interpretation  
- These models help reduce subjectivity and error in clinical fetal monitoring  
- Integration into healthcare workflows can support timely, data-driven decisions  

---

## 🚀 Future Work

- Validate models in real-time clinical settings  
- Explore ensemble and deep learning methods  
- Combine with multimodal data (e.g., fetal ECG)  
- Develop interpretable AI tools for medical professionals  

---

## 📚 References

1. UCI Machine Learning Repository - Cardiotocography Dataset  
2. Chanyaswad, T. et al. (2018). *Differential Privacy Mechanism Design*. arXiv.  
3. Clémençon, S. & Robbiano, S. (2015). *The TreeRank Tournament Algorithm*.  
4. Lisboa, P. et al. (2013). *Reproducible Cluster Partitions for k-Means*.

---

## 👨‍💻 Author

**Prakhyat Singh**  
B.Tech, Computer Science and Engineering  
Lovely Professional University  
*Roll No: RKM068B44 | Reg. No: 12218463*

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
****
