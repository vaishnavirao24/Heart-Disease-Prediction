# 🏥 Health Disease Prediction  

A machine learning-based classification model that predicts the likelihood of a person having heart disease based on medical attributes such as age, cholesterol levels, blood pressure, and more. The model uses **Random Forest, Support Vector Machine (SVM), and Logistic Regression** to provide predictions with high accuracy.  

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
git clone https://github.com/vaishhnavirao24/health-disease-prediction.git
cd health-disease-prediction

# Install dependencies
pip install -r requirements.txt

# Run the script
python main.py
```

## 📝 How It Works  

### 📌 Dataset
Uses a heart disease dataset with 13 medical features including:
- Age 
- Cholesterol levels 
- Blood pressure 
- Maximum heart rate 
- Chest pain type 
- Exercise-induced angina

### 📌 Feature Engineering
1. **Cholesterol-to-Age Ratio**: Created a new feature by dividing cholesterol by age
2. **Age Groups**: Categorized age into bins (30-39, 40-49, 50-59, 60+)
3. **Blood Pressure Categories**: Classified into normal, elevated, and high

### 📌 Preprocessing
1. Handled missing values using median imputation
2. One-hot encoded categorical variables
3. Standardized numerical features using StandardScaler
4. Split data into 80% training and 20% testing sets

### 📌 Model Training & Evaluation
1. Trained three classifiers:
   - Random Forest (100 trees)
   - SVM (RBF kernel)
   - Logistic Regression
2. Evaluated using:
   - Accuracy score
   - Confusion matrix
   - AUC-ROC curves
   - Precision, Recall, and F1-score metrics

## 📊 Model Performance  
| Model               | Accuracy (%) | AUC-ROC Score |
|---------------------|--------------|---------------|
| Random Forest       | 81.96        | 92.29         |
| SVM                 | 88.52        | 92.24         |
| Logistic Regression | 86.79        | -             |

## 🤝 Contributing  
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request
