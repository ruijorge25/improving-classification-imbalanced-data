# improving-classification-imbalanced-data
Comparative study on improving classification performance under data imbalance, using preprocessing, imputation, oversampling (SMOTE), and model evaluation.

⚖️ Improving Classification with Imbalanced Data — AC1 Project

This project explores how to improve the performance of classification algorithms when faced with imbalanced datasets, using a set of data processing techniques and model evaluations. It was developed as part of the Machine Learning I course (AC1), with emphasis on comparative analysis and real-world dataset challenges.

🎯 Objective
To test various classification algorithms under different preprocessing scenarios, particularly focusing on data imbalance. The project compares performance metrics across models trained on raw, cleaned, imputed, and balanced datasets.

📚 Algorithms Tested
Logistic Regression
Random Forest
Gradient Boosting
k-Nearest Neighbors (KNN)
Decision Tree

Naive Bayes

🧪 Data Variants Created (via preprocessing)
Original dataset
Cleaned dataset (removed outliers and duplicates)
Imputed dataset (missing values handled)
Balanced dataset (using oversampling and SMOTE)

🔍 Key Insights
Algorithms like Gradient Boosting and Random Forest consistently outperformed others.
Data cleaning and balancing led to significant gains in precision and recall.
The HTML report (relatorio_comparativo_final.html) includes detailed metrics and visual comparisons for all tested configurations.

📁 Repository Structure
data/
└── class_imbalance/ → Original dataset (keep only this folder)

notebooks/
└── Improving_Classification_Algorithm_Final.ipynb

outputs/
└── relatorio_comparativo_final.html → Final report with all evaluation results

docs/
└── PracticalAssignment_ML1.pdf → Assignment instructions

slides/
└── PowerPoint Apresentation.pptx → Optional presentation

README.md

🧰 Requirements
Python 3.x
Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

▶️ How to Run

Clone the repository:
git clone https://github.com/ruijorge25/improving-classification-imbalanced-data.git
cd improving-classification-imbalanced-data

Launch the notebook:
jupyter notebook notebooks/Improving_Classification_Algorithm_Final.ipynb
Run all cells in order to:
Load and preprocess data
Train models on different variants
Evaluate using metrics and confusion matrices
View and compare results

📊 Evaluation Metrics Used
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
ROC-AUC Curve

👥 Authors
Pedro Ferreira Oliveira Amaro
Rui Jorge Marques de Almeida
