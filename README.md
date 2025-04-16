# 🧮 Credit Risk Modeling: Give Me Some Credit Dataset

This repository contains a complete end-to-end machine learning pipeline to **predict the risk of serious credit delinquency within the next two years**, based on the [Give Me Some Credit dataset](https://www.kaggle.com/c/GiveMeSomeCredit) from Kaggle.

I perform **EDA, preprocessing, feature engineering, class balancing, model training, hyperparameter tuning, SHAP explainability**, and build a deployable **Streamlit application** for real-time prediction.

---

## 📌 Key Highlights

- 📊 **Exploratory Data Analysis**: Univariate, bivariate, and correlation heatmaps
- 🧹 **Data Preprocessing**: Imputation, scaling, SMOTE for class imbalance
- 🤖 **Modeling**: Random Forest classifier with GridSearchCV tuning
- 📈 **Evaluation**: Confusion matrix, classification report, ROC AUC score
- 🔍 **Explainability**: Model interpretability via SHAP values
- 🖥 **Deployment**: Interactive Streamlit app with prediction and SHAP visualization

---

## 🔧 Technologies Used

- Python 3.9+
- Scikit-learn
- Imbalanced-learn (SMOTE)
- SHAP
- Streamlit
- Pandas, NumPy, Seaborn, Matplotlib

---

## 📁 Folder Structure

credit-risk-modeling/
│
├── app.py                     # Streamlit application
├── model_training.ipynb       # Model training and evaluation
├── eda_notebook.ipynb         # Exploratory Data Analysis
├── data/
│   └── cs-training.csv        # Raw dataset
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation


---

## 🚀 How to Run the App

1. **Clone the repository**

```bash
git clone https://github.com/your-username/credit-risk-modeling.git
cd credit-risk-modeling
```

### 2. Install dependencies
```
pip install -r requirements.txt
```
### 3. Run the Streamlit app
```
streamlit run app.py
```

## 🙏 Acknowledgments
Give Me Some Credit - Kaggle dataset

SHAP for interpretability

## 📬 Contact
Author: Ruairí McConville
📧 mcconvilleruairi@gmail.com
🔗 LinkedIn • GitHub




![image](https://github.com/user-attachments/assets/623dd394-f7de-45b2-ba0f-593d5ed8f4ab)


![image](https://github.com/user-attachments/assets/ed7266c6-655d-4ff6-bc31-fe025665213f)


![image](https://github.com/user-attachments/assets/4fdf9a31-f28e-48a3-9cb9-2dcb5188280d)


![image](https://github.com/user-attachments/assets/c2ec2d2c-2010-4215-8c8a-85b50c056d52)

