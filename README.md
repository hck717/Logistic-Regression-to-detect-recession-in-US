# Logistic-Regression-to-detect-recession-in-US
📈 Predicting U.S. Recessions with Logistic Regression: A Data-Driven Approach

📈 Predicting U.S. Recessions with Logistic Regression: A Data-Driven Approach

I’m excited to share insights from my recent project where I developed a logistic regression model to predict recessions in the U.S. economy. This project combines the data science techniques I learned in the course COMP3314 at HKU with self-taught economic analysis to make informed forecasts. I completed this work with the assistance of Grok3 and various online resources. Here’s a breakdown of the process:


1. Data Science Workflow

The project involved several critical steps:
-Data Collection: Utilized the FRED API to gather key economic indicators from 1960 to 2025.
-Data Preprocessing: Cleaned and transformed the data into quarterly percentage changes for analysis.


2. Key Features for Prediction

I selected the following features to enhance the model's predictive capabilities:
-Payroll Employment: Total number of paid employees, indicating economic health.
-Personal Income Less Transfers: Disposable income available for consumption.
-Manufacturing and Trade Sales: Sales activity in key sectors reflecting economic performance.
-Industrial Production: Output measure from industrial sectors.
-Lagged Features: Included lagged values for payroll and income to capture past trends.
-Interaction Terms: Combined effects of features to reveal deeper economic relationships.


3. Model Evaluation Metrics

To assess the model's performance, I employed several metrics:

- Accuracy: The model achieved an impressive 100% accuracy in backtesting.
- ROC-AUC Score: A perfect score of 1.0, demonstrating the model’s ability to classify recession periods accurately.
- Confusion Matrix: Analyzed true positives, true negatives, false positives, and false negatives to understand model errors.
- Optimal C Parameter: Identified through GridSearchCV, optimizing model performance.


4. Tech Stack
The project utilized a robust tech stack:

Programming Language: 
-Python
Libraries:
-pandas, numpy for data manipulation
-matplotlib, seaborn for visualization
-scikit-learn for machine learning and model evaluation
-statsmodels for statistical analysis
-fredapi for accessing economic data


5. Results and Visualization

The model's predictions were visualized through various plots, showcasing trends in economic indicators, predicted recession probabilities, and feature importance. Key findings included:
-Backtest Performance: Analyzed from 1960 to 2025, validating the model’s robustness.


I undertook this project with the aim of leveraging my ML knowledge to analyze real-life scenarios. While the predictions may not be perfect and there are many areas for improvement, I am committed to continuing my journey by working on various projects to enhance my hands-on experience with ML and data.

Feel free to drop any suggestions or advice—I'm eager to learn and grow! Thank you for reading my post! ^^


hashtag#DataScience hashtag#MachineLearning hashtag#Economics hashtag#LogisticRegression hashtag#RecessionPrediction hashtag#Python
