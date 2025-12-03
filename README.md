# Loan-Default-Prediction-Machine-Learning-Project
 This project predicts whether a borrower is likely to **default** or **repay** a loan using Machine Learning.   The model analyzes key financial and demographic factors such as **credit score, income, loan amount, employment years**, and more.

  🚀 Project Overview
This end-to-end ML pipeline includes:

- Synthetic dataset generation  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Model training (Multiple ML algorithms)  
- Performance evaluation  
- Data visualization  
- ROC-AUC comparison  

---

## 🎯 Objective
To help banks & financial institutions estimate **loan default risk** early and make smarter lending decisions.

---

## 📁 Dataset Features
The dataset contains 2000+ synthetic records with fields like:

- Age  
- Income  
- Loan Amount  
- Loan Term (in months)  
- Employment Years  
- Credit Score  
- Interest Rate  
- Marital Status  
- Purpose (Business, Education, Medical, Home, etc.)  
- **loan_default** (0 = No, 1 = Yes)

---

## 🔧 Tech Stack
- **Python**
- **NumPy**
- **Pandas**
- **Scikit-Learn**
- **Matplotlib / Seaborn**

---

## 📌 Machine Learning Models Used
| Model | Used |
|------|------|
| Logistic Regression | ✔ |
| Random Forest | ✔ |
| Gradient Boosting | ✔ |
| Support Vector Machine | ✔ |
| XGBoost (optional) | ✔ |

---

## 📈 Model Evaluation Metrics
The following metrics were used to compare models:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC-AUC Score  

---

## 🏆 Best Performing Model
### **Random Forest Classifier**

- Highest accuracy  
- Best ROC curve  
- Great for non-linear patterns  
- Handles imbalanced data well  

---

## 📊 Data Visualization
The project includes:

- Histogram (Loan Amount Distribution)  
- Bar Graph (Loan Purposes)  
- Line Chart (Age vs Income)  
- Box Plot (Credit Score Distribution)  
- ROC Curve for all models  

---

## 📥 Installation

```bash
pip install numpy pandas scikit-learn matplotlib seaborn xgboost
```

---

## ▶ Run the Project

```bash
jupyter notebook Loan_Prediction.ipynb
```

---

## ✨ Key Insights
- Low credit score + high loan amount → high default risk  
- High income → reduces chance of default  
- Interest rate & loan purpose influence repayment  
- Employment years strongly correlate with trustworthiness  

---

## 💡 Conclusion
This project successfully demonstrates a full ML pipeline and identifies the **Random Forest Model** as the best fit for loan default prediction.

---

## 🤝 Connect With Me  
📌 **Ashish Kumar**  
- GitHub: https://github.com/Ashishkumar4u  
- LinkedIn: *(Add your link here)*  

Feel free to ⭐ the repository if you found it useful!
