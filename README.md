# FinGuard – Financial Bankruptcy Prediction System

FinGuard is a machine learning-based web application that predicts the bankruptcy risk of a company using financial indicators. The project leverages XGBoost for classification and provides an intuitive Flask-based interface for real-time predictions.

## Features

- Predicts company bankruptcy risk using financial statement data
- Trained using the XGBoost classification algorithm
- Handles class imbalance using SMOTE
- Hyperparameter tuning using RandomizedSearchCV
- Interactive web interface built with Flask
- Model deployed locally and exposed using ngrok
- Model persistence using Joblib

---

## Tech Stack

- Python
- Scikit-learn
- XGBoost
- Flask
- Pandas
- NumPy
- Matplotlib
- SHAP
- imbalanced-learn (SMOTE)
- Joblib
- ngrok

---

## Model Performance

| Metric | Score |
|---------|------:|
| Accuracy | **92.05%** |
| ROC-AUC | **0.8893** |
| Precision | **0.4291** |
| Recall | **0.5996** |
| F1-Score | **0.5002** |

---

## Machine Learning Pipeline

1. Data preprocessing and cleaning
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Handling class imbalance using SMOTE
5. Train-test split
6. Hyperparameter tuning using RandomizedSearchCV
7. XGBoost model training
8. Model evaluation
9. Model serialization using Joblib
10. Prediction through Flask web application



---

## Future Improvements

- Deploy on Render or Hugging Face Spaces
- Add user authentication
- Support CSV upload for batch predictions
- Improve model interpretability dashboard
- Compare additional ensemble models

---

<img width="1381" height="697" alt="image" src="https://github.com/user-attachments/assets/b8a2c923-96e3-44c9-84f9-efcd9502250a" />
<img width="1247" height="691" alt="image" src="https://github.com/user-attachments/assets/7519eb3d-52a5-4047-8dd6-fe7fffdac2f7" />
<img width="1360" height="752" alt="image" src="https://github.com/user-attachments/assets/03df1f29-cc18-4892-a12d-a8027652ae74" />
<img width="1382" height="725" alt="image" src="https://github.com/user-attachments/assets/c570e94f-b4fc-4106-872d-ba8ae9459593" />
<img width="1380" height="673" alt="image" src="https://github.com/user-attachments/assets/213c4395-b3ea-4a9e-b3dd-4aace93b3862" />

