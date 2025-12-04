Diabetes Prediction App (Logistic Regression)  
This project predicts the likelihood of diabetes based on medical parameters using Logistic Regression.  

App URL: https://aexsttdodpklttbgnmydecy.streamlit.app  

Features Used:-  
1.Pregnancies  
2.Glucose  
3.Blood Pressure  
4.Skin Thickness  
5.Insulin  
6.BMI  
7.Diabetes Pedigree Function  
8.Age  

Model Details:-  
Algorithm: Logistic Regression  
Scaling: StandardScaler  
Target Variable: Outcome (0 = No Diabetes, 1 = Diabetes)  
Dataset: PIMA Diabetes Dataset  

Project Structure:-  
app.py              # Streamlit frontend code  
logistic_model.pkl  # Saved ML model  
scaler.pkl          # Saved StandardScaler  
requirements.txt    # Dependencies for Streamlit Cloud  
