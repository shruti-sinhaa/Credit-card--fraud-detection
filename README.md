# Credit-card--fraud-detection

# 📌 Project Overview

This project focuses on building a machine learning–based fraud detection system to identify fraudulent credit card transactions.
The goal is to handle highly imbalanced data, improve fraud recall, and minimize false negatives while maintaining strong overall performance.

The model analyzes transaction patterns and predicts whether a transaction is fraudulent or legitimate, helping financial institutions reduce losses and improve security.

# 🧠 Problem Statement

Credit card fraud datasets are highly imbalanced, where fraudulent transactions represent a very small percentage of total transactions.
Traditional models often achieve high accuracy but fail to detect fraud effectively.

# Challenges addressed:
- Severe class imbalance
- Low recall for fraud cases
- Need for reliable evaluation metrics beyond accuracy

# 📂 Dataset

- Publicly available credit card transaction dataset
- Contains anonymized numerical features
- Highly imbalanced class distribution:
- Legitimate transactions ≫ Fraudulent transactions

# Target variable:

- Class = 1 → Fraud
- Class = 0 → Legitimate

# ⚙️ Technologies & Tools Used

-Programming Language: Python
-Libraries: Pandas, NumPy – data handling
- scikit-learn – model building & evaluation
- imbalanced-learn (SMOTE) – handling class imbalance

Visualization: Matplotlib / Seaborn

# 🔄 Project Workflow

# 1️⃣ Data Preprocessing
- Checked for missing and duplicate values
- Feature scaling for better model performance

Analyzed class imbalance

# 2️⃣ Handling Imbalanced Data
- Applied SMOTE (Synthetic Minority Oversampling Technique)
- Balanced minority (fraud) and majority (non-fraud) classes to improve model learning

# 3️⃣ Model Training
- Trained and evaluated multiple machine learning models such as:
- Logistic Regression
- Random Forest / other classifiers (if applicable)

# 4️⃣ Model Evaluation
- Used metrics suitable for imbalanced datasets:
-Precision
- Recall
- F1-Score
- ROC-AUC Score

# 📊 Results & Performance
- Achieved high ROC-AUC score (~0.985) indicating strong classification ability
- Improved recall for fraudulent transactions, reducing false negatives
- Balanced trade-off between precision and recall using SMOTE
- Accuracy was not used as the primary metric due to class imbalance.

- 🔍 Key Insights
- SMOTE significantly improved fraud detection performance
- Recall is a critical metric in fraud detection systems
- Proper preprocessing and evaluation are crucial for real-world ML problems

# 🚀 Future Improvements
- Implement real-time fraud detection pipeline
- Experiment with advanced models (XGBoost, Neural Networks)
- Add cost-sensitive learning
- Deploy the model as a REST API
-Integrate transaction streaming data

# Clone the repository  
Git Clone 
```bash https://github.com/shruti-sinhaa/Credit-card--fraud-detection.git
```

# 👩‍💻 About
💼 LinkedIn: [Shruti Sinha](www.linkedin.com/in/shruti-sinha24)

Let’s connect professionally and grow!
 💡 Thanks for checking out the project! Your support means a lot — feel free to star ⭐ this repo or share it with someone.🚀


