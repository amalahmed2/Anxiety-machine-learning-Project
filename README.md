# Anxiety Prediction ML Project 
Anxiety Prediction Using Machine Learning  (CBIO313 Project )
This project uses machine learning models to predict anxiety levels based on psychological questionnaire data. It was developed as part of a final university project using multiple classifiers and deployed via a Streamlit web application.

## 📂 Project Structure

```
anxiety-ml-project/
├── Aotebook.ipynb          # Full ML pipeline from preprocessing to model evaluation
├── app.py                  # Streamlit deployment script
├── anxiety.csv             # Dataset used for training/testing
├── xgb_model.pkl           # Trained XGBoost model
├── rf_model.pkl            # Trained Random Forest model
├── scaler.pkl              # Scaler used during preprocessing
├── video.link              # Project explanation video 
└── README.md               # Project documentation
```

## 🧠 Models Used

- XGBoost (highest accuracy)
- Random Forest
- Logistic Regression
- SVM
- Naive Bayes

## ✅ Features

- Data preprocessing and scaling
- Feature selection
- Model evaluation with confusion matrix & classification reports
- Interactive Streamlit web app
- Allows user to upload CSV and choose between top models

## Deployment

Run the app locally with:
```bash
streamlit run app.py
```

## 📊 Dataset Info

The dataset includes various psychological factors collected via questionnaires to classify anxiety into binary levels.

## 📽️ Video

Watch the full project presentation here:  
[📺 Click to watch] (.......)  
The video  explanation of the project, including problem definition, workflow, models used, results and the Streamlit app.
---
# Developed by: Amal Ahmed
