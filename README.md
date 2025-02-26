# Disease-diagnosis-model
This project is a disease diagnosis model that predicts whether a person has diabetes based on health indicators such as glucose levels, BMI, insulin, blood pressure, and age. It uses a Random Forest Classifier trained on the PIMA Indians Diabetes Dataset.


disease-diagnosis-model/
│── data_loading.txt               # Load dataset into Pandas
│── data_preprocessing.txt         # Handle missing values and scale features
│── data_visualization.txt         # Generate heatmaps and distribution plots
│── train_test_split.txt           # Split data into training and testing sets
│── model_training.txt             # Train the Random Forest model
│── model_evaluation.txt           # Evaluate model performance
│── pipeline_model.txt             # ML pipeline with scaling and classification
│── bmi_classification.txt         # Categorize BMI into health groups
│── lifestyle_recommendations.txt  # Provide health advice based on predictions
│── diabetes.csv                   # Dataset (if allowed to upload)
│── README.md                      # Project documentation
│── requirements.txt                # List of required dependencies


 Features:
 Data Preprocessing (Handling missing values, Feature Scaling)
 Exploratory Data Analysis (EDA) with Seaborn & Matplotlib
 Machine Learning using Random Forest Classifier
 Model Evaluation (Confusion Matrix, Classification Report)
 Health & Lifestyle Recommendations Based on Predictions


 Dataset Information
The dataset contains 768 patient records with the following features:
Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI (Body Mass Index)
Diabetes Pedigree Function
Age
Outcome (0 = No Diabetes, 1 = Diabetes)


