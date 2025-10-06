# Heart_Disease-_Project
Heart Disease Prediction using Logistic Regression. This project includes data analysis, preprocessing, and model building to classify heart disease presence. Dashboard visualizations created with Python libraries like Matplotlib and Seaborn. Achieved high accuracy.

This project aims to predict the presence of heart disease using a Logistic Regression model. It follows a complete machine learning pipeline—from exploratory data analysis (EDA) to model deployment—designed to deliver actionable insights and high classification accuracy.

🔍 Exploratory Data Analysis
I began by analyzing the dataset to uncover patterns and relationships:

- Average Age: 53.5 years
- Average Heart Rate: 136.8 bpm
- Total Patients: 918

Key Visual Insights from the Dashboard:
- Sex Distribution: 79% male, 21% female
- Heart Disease Prevalence: 44% of patients had heart disease

Chest Pain Types:
- Atypical Angina (ATA): 22.1%
- Non-Anginal Pain (NAP): 18.8%
- Asymptomatic (ASY): 54%
- Typical Angina (TA): 5.1%

Resting ECG Results:
- Normal, ST, and LVH patterns vary by sex and disease presence
- Oldpeak vs Age: Older patients tend to show higher ST depression values
- Cholesterol vs RestingBP: No clear linear trend, but clustering suggests risk zones

These visualizations were built using Matplotlib and Seaborn, offering a clear view of feature distributions and correlations.

🧼 Data Preprocessing
1) Handled missing values and encoded categorical features
2) Scaled numerical features for optimal model performance
3) Split data into training and test sets

🧠 Model Building
1) Used Logistic Regression for binary classification
2) Tuned hyperparameters to improve accuracy
3) Evaluated using metrics like accuracy, precision, recall, and ROC-AUC

✅ Results
- Achieved high accuracy in predicting heart disease
- Model interpretable and deployable for real-world use
