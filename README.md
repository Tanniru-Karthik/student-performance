Student Performance Prediction using Linear Regression
Project Overview

This project aims to predict student performance (total_score) using Machine Learning techniques. A Linear Regression model is applied to analyze how factors such as study hours, attendance, class participation, and grade influence a student’s overall score.

📁 Dataset Information
Source: Kaggle
File Name: student_performance.csv
 Note: The dataset is not included in this repository due to file size limitations. Please download it manually.
📥 Dataset Setup
Download the dataset from Kaggle
Place student_performance.csv in the project directory before running the code
🧾 Features
student_id
weekly_self_study_hours
attendance_percentage
class_participation
grade
Target Variable
total_score
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
⚙️ Workflow
Import required libraries
Load the dataset
Handle missing values
Encode categorical variables
Split dataset into training and testing sets
Train the Linear Regression model
Make predictions
Evaluate model performance
Visualize results
📏 Evaluation Metrics
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score
📈 Sample Output
MAE  : 4.2
MSE  : 30.5
RMSE : 5.5
R²   : 0.82
📊 Visualization

A scatter plot is used to compare actual vs predicted scores, helping to visually assess model accuracy.

✅ Conclusion

Linear Regression proves to be a simple yet effective model for predicting student performance when relationships between variables are linear. However, it may struggle with capturing complex, non-linear patterns in the data.

Future Improvements
Implement advanced models like Random Forest or XGBoost
Perform hyperparameter tuning
Apply feature engineering techniques
Improve prediction accuracy with cross-validation
How to Run
Download the dataset from Kaggle
Place student_performance.csv in the project folder

Install required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

Run the Python script:

python main.py
