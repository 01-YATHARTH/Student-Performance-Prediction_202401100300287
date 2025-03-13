Student Performance Prediction


Problem Statement


In the education system, predicting student performance is essential for early intervention and academic planning. Teachers, parents, and educational institutions can benefit from a model that forecasts final exam scores based on students' study habits and previous academic records.

This project builds a Machine Learning model using Linear Regression to predict students' final exam scores based on two key factors:

Study Hours: The number of hours a student has studied.
Previous Scores: The student's past exam performance.
The model helps identify students at risk of poor performance and allows educators to take timely actions to improve learning outcomes.

Features of the Project
This project includes:
✔️ Automatic dataset loading in Google Colab after user uploads the file.
✔️ Feature extraction from student data (Study Hours, Previous Scores).
✔️ Data Splitting: 80% training & 20% testing.
✔️ Linear Regression Model for score prediction.
✔️ Model evaluation metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
✔️ Visualization: Scatter plot comparing actual vs predicted scores.
Dataset Details
The dataset consists of three main columns:

StudyHours: The number of hours a student studied.
PreviousScores: The student’s previous exam scores.
FinalExamScore: The actual final exam score (target variable).
Requirements
Before running the script, install the required Python libraries:

bash
Copy
Edit
pip install pandas numpy matplotlib scikit-learn
Usage Instructions
Upload the dataset in Google Colab before running the script.
Run the code to train and evaluate the Linear Regression model.
The model will output evaluation metrics and a scatter plot comparing actual vs predicted scores.
Code Workflow
Step 1: Load the dataset (already uploaded in Google Colab).
Step 2: Extract StudyHours and PreviousScores as features and FinalExamScore as the target variable.
Step 3: Split the dataset into training (80%) and testing (20%) sets.
Step 4: Train a Linear Regression model using scikit-learn.
Step 5: Predict scores on the test set.
Step 6: Evaluate performance using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Step 7: Plot Actual vs Predicted Scores.
Model Evaluation Metrics
The model is evaluated using the following metrics:
📌 Mean Absolute Error (MAE) – Measures average absolute difference between actual & predicted values.
📌 Mean Squared Error (MSE) – Measures average squared difference between actual & predicted values.
📌 Root Mean Squared Error (RMSE) – Measures standard deviation of residuals (prediction errors).


Conclusion
This project demonstrates how Linear Regression can predict student performance based on study hours and previous scores. Educators can use this model to identify struggling students early and provide targeted academic support.
