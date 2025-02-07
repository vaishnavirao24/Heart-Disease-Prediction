# 🏥 Health Disease Prediction  

A machine learning-based classification model that predicts the likelihood of a person having heart disease based on medical attributes such as age, cholesterol levels, blood pressure, and more. The model uses **Random Forest, Support Vector Machine (SVM), and Logistic Regression** to provide predictions with high accuracy.  

## 🎯 Demo  
*(Add a screenshot or confusion matrix visualization here!)*  

## 🚀 Features  
✔️ Predicts heart disease likelihood based on patient data  
✔️ Implements **Random Forest, SVM, and Logistic Regression** models  
✔️ Uses **feature engineering** (e.g., Cholesterol-to-Age ratio, Age Groups)  
✔️ Evaluates model performance using **confusion matrix, AUC-ROC, and classification reports**  
✔️ Data preprocessing includes **scaling, one-hot encoding, and missing value handling**  

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries Used:** pandas, NumPy, seaborn, matplotlib, scikit-learn  

## 📥 Installation  

```bash
# Clone the repository
git clone https://github.com/your-username/health-disease-prediction.git
cd health-disease-prediction

# Install dependencies
pip install -r requirements.txt

# Run the script
python main.py

📝 How It Works
📌 Dataset
Uses a heart disease dataset with features like age, cholesterol, and blood pressure.
📌 Feature Engineering
Created a new feature: Cholesterol-to-Age ratio
Categorized age into groups (30-39, 40-49, etc.)
📌 Preprocessing
One-hot encoding for categorical variables
Standardization of numerical features
📌 Model Training & Evaluation
Trains Random Forest, SVM, and Logistic Regression models
Evaluates performance using accuracy, confusion matrix, and AUC-ROC scores
📊 Model Performance
Model	Accuracy (%)	AUC-ROC Score
Random Forest	81.96	92.29
SVM	88.52	92.24
Logistic Regression	86.79	-
🤝 Contributing
Feel free to fork the repo and submit a pull request if you have improvements!
