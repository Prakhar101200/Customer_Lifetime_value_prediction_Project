Customer Lifetime Value Prediction Project
Overview
This project aims to predict the Customer Lifetime Value (CLV) for an Auto Insurance Company in the USA. Customer Lifetime Value represents a customer’s value to a company over a period, and it is a crucial metric for businesses to improve customer retention, increase revenue, and enhance overall customer experience. The project includes data analysis, model training, evaluation, and interpretation.

Key Insights
The Random Forest model achieved the highest R-squared score of 0.904 and RSME score of 0.207, demonstrating its effectiveness in predicting CLV.
We successfully predicted the CLV score for a single test data point and compared it with the actual CLV, showing high accuracy.
The most significant features in predicting CLV are 'Number of Policies' and 'Monthly Premium Auto', as per feature importance analysis.
Methodology
Data Analysis: Explored data using seaborn and matplotlib to visualize relationships between features and CLV.
Model Training: Trained various regression models including Linear Regression, Support Vector Machine, Lasso Regression, Decision Tree, Random Forest, and Adaboost Regressor.
Hyperparameter Tuning: Due to computational limitations, we couldn't perform hyperparameter tuning. However, Random Forest without tuning provided the best accuracy.
Feature Importance: Identified the most influential features using feature importance scores from the Random Forest model.
Prediction: Utilized the trained Random Forest model to predict CLV for a single test record with high accuracy.
Project Limitations
Computational limitations prevented us from performing hyperparameter tuning for the Random Forest model.
Despite limitations, we achieved high accuracy with the Random Forest model.
Libraries Used
pandas: Data manipulation and analysis.
numpy: Numerical calculations and array operations.
seaborn, matplotlib: Data visualization.
scipy, statsmodel: Statistical analysis and hypothesis testing.
Usage
Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the Jupyter notebooks to explore the data, train models, and make predictions.
Acknowledgments
Dataset source: Auto Insurance Company
License
This project is licensed under the MIT License - see the LICENSE file for details.
