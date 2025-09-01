# titanic-survival-prediction
# 🚢 Titanic Survival Prediction  

Predict which passengers survived the Titanic disaster using **Machine Learning**.  
This project is based on the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic).  

---

## 📌 Project Overview  
The goal of this project is to build a **classification model** that predicts survival based on passenger features like age, sex, ticket class, family size, etc.  

Key steps in the project:  
- Data Cleaning & Handling Missing Values  
- Feature Engineering (e.g., extracting titles from names, creating FamilySize)  
- Model Building (Logistic Regression, Random Forest, Gradient Boosting)  
- Model Evaluation (Accuracy, ROC-AUC, Confusion Matrix)  

---

## 📂 Repository Structure  
titanic-survival-prediction/
│── README.md # Project documentation
│── requirements.txt # Dependencies
│── notebooks/ # Jupyter notebooks (EDA, Feature Engineering, Modeling)
│── src/ # Python scripts (training & prediction)
│── outputs/ # Saved figures & predictions
│── models/ # Trained ML models





■ Titanic Survival Prediction
Project Overview
This project predicts whether a passenger survived the Titanic disaster using Machine Learning
models.
Dataset
The dataset is from the Kaggle Titanic Competition (https://www.kaggle.com/c/titanic).
Files required: train.csv and test.csv (to be placed inside the data/ folder).
How to Run
1. Clone the repo: git clone https://github.com//titanic-survival-prediction.git
2. cd titanic-survival-prediction
3. Install dependencies: pip install -r requirements.txt
4. Run notebooks: jupyter notebook
5. Train the model: python src/train.py
Results
Model Accuracy ROC-AUC
Logistic Regression 79% 0.83
Random Forest 82% 0.86
Gradient Boosting 84% 0.88
Visualizations (EDA)
• Survival rate by Gender → Women survived more.
• Survival rate by Class → 1st class had better survival.
• Age distribution shows children had higher survival chances.
Future Work
• Tune hyperparameters
• Add XGBoost / LightGBM models
• Build a Streamlit web app for predictions
License
MIT License – free to use & modify.
