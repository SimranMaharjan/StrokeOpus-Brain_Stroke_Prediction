🧠 StrokeOpus: Brain Stroke Prediction Using Machine Learning
This is a full-stack web application for predicting the likelihood of a brain stroke using a Random Forest classifier. The machine learning model was trained on a Kaggle stroke dataset containing patient health and lifestyle features. The model is integrated into a Flask backend, while the frontend is developed using React.

The application accepts user input through the React UI, applies one-hot encoding to categorical variables, and forwards the processed data to the backend where it is passed into a pre-trained model serialized using Pickle. The output is a binary classification indicating the presence or absence of stroke risk.

📊 Features Used for Prediction:
Age

Gender

Heart Disease

Average Glucose Level

Body Mass Index (BMI)

Marital Status

Residence Type

Work Type

Hypertension

Smoking Status

🧪 Tech Stack:
Frontend: React

Backend: Flask

Machine Learning: Random Forest 

Libraries: pandas, NumPy, scikit-learn

Model Serialization: Pickle

📈 Evaluation Metrics:
Accuracy

Precision

Recall

F1 Score

Confusion Matrix
