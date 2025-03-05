🏥 Disease Prediction using Machine Learning

📌 Overview

This repository contains a Streamlit web app that predicts Heart Disease, Diabetes, and Parkinson's Disease using pre-trained Machine Learning models. The models are saved as .sav files and are loaded in app.py for making predictions.

🔍 Files in This Repository

app.py – The main Streamlit application for user input and predictions.

heart_model.sav – Pre-trained model for Heart Disease prediction.

diabetes_model.sav – Pre-trained model for Diabetes prediction.

parkinsons_model.sav – Pre-trained model for Parkinson's Disease prediction.


🚀 How to Run the App

1️⃣ Clone the Repository

git clone https://github.com/yourusername/disease-prediction.git  
cd disease-prediction

2️⃣ Install Dependencies

pip install streamlit pandas numpy scikit-learn

3️⃣ Run the Streamlit App

streamlit run app.py

⚡ How It Works

1. The pre-trained models (saved as .sav files) are loaded in app.py.


2. The user enters medical parameters in the Streamlit UI.


3. The app processes the input and predicts whether the user is at risk of Heart Disease, Diabetes, or Parkinson’s Disease.



🎯 Future Enhancements

Deploy the app on cloud platforms (AWS/GCP).

Add more diseases for prediction.


📜 License

This project is open-source. Feel free to contribute!


---
