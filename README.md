🧠 Cardiotocography Analysis using Machine Learning
This project explores the application of various machine learning classifiers to analyze Cardiotocography (CTG) data for improving fetal monitoring during pregnancy and labor. By automating CTG interpretation, we aim to assist healthcare professionals in making accurate, timely decisions and ultimately enhance maternal and neonatal outcomes.

📊 Project Overview
Domain: Medical / Machine Learning

Dataset: UCI Machine Learning Repository - Cardiotocography Data

Tech Stack: Python, NumPy, pandas, matplotlib, scikit-learn, Jupyter Notebook

Classifiers Used:

Perceptron

Logistic Regression

Support Vector Machine (SVM)

k-Nearest Neighbors (KNN)

Decision Tree

🧪 Methodology
⚙️ Hardware & Software
Processor: AMD Ryzen 9 5900HX

GPU: NVIDIA GeForce RTX 3060

RAM: 16GB

OS: Windows 11

IDE: Jupyter Notebook

🗂️ Data Preprocessing
2126 labeled CTG records categorized as:

Normal (1)

Suspect (2)

Pathologic (3)

StandardScaler used for feature scaling.

Train-test split: 80:20.

📈 Model Training & Evaluation
Metrics used: Accuracy, Precision, Recall, F1 Score

GridSearchCV for hyperparameter tuning

5-fold cross-validation for robustness assessment

✅ Results
Classifier	Training Accuracy	Testing Accuracy
Perceptron	89.12%	84.98%
Logistic Regression	90.71%	87.79%
SVM	93.53%	90.38%
KNN	93.18%	91.55%
Decision Tree	93.82%	90.14%

KNN performed best on testing data.

SVM and Decision Tree showed excellent robustness and generalization.

Cross-validation confirmed high average accuracy across folds.

📌 Key Takeaways
Machine Learning models, especially SVM, KNN, and Decision Tree, are highly effective in interpreting CTG data.

These models can reduce human error and subjectivity in fetal state assessment.

Incorporating ML into obstetric care can assist in timely clinical interventions.

🚀 Future Work
Clinical validation with real-time CTG data.

Integration with multimodal data (e.g., ECG).

Exploration of ensemble and deep learning models.

Development of interpretable models for better clinical adoption.

📚 References
UCI Machine Learning Repository - Cardiotocography Data

Chanyaswad et al., (2018). A Differential Privacy Mechanism Design Under Matrix-Valued Query.

Clémençon & Robbiano, (2015). The TreeRank Tournament algorithm.

Lisboa et al., (2013). Finding reproducible cluster partitions for k-means.

👨‍💻 Author
Prakhyat Singh
B.Tech in Computer Science and Engineering
Lovely Professional University
