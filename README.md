House Price Prediction - Regression Models
This project predicts house prices using the Boston Housing Dataset. We compare three models: Linear Regression, Random Forest, and XGBoost.
Steps
1.	Data Preprocessing:
o	Normalization: Scaled numerical features using Min-Max normalization.
o	Train-Test Split: 80% training, 20% testing.
2.	Model Implementation:
o	Linear Regression: Solved using matrix algebra.
o	Random Forest: Ensemble of decision trees trained on bootstrap samples.
o	XGBoost: Simplified version of gradient boosting.
3.	Evaluation:
o	Metrics: RMSE (Root Mean Squared Error) and R² (Coefficient of Determination).
4.	Feature Importance: Visualized the feature importance for the Random Forest model.
How to Run
Prerequisites
Install required libraries:
bash
CopyEdit
pip install pandas numpy matplotlib scikit-learn
Running the Script
1.	Download the Boston Housing Dataset (CSV format) and update the file path in the script.
2.	Run the script:
bash
CopyEdit
python house_price_prediction.py
3.	The script will output RMSE and R² for each model and display a feature importance plot for Random Forest.
Observations
1.	Linear Regression:
o	RMSE: 0.1246, R²: 0.6271
2.	Random Forest:
o	RMSE: 0.1219, R²: 0.6430
3.	XGBoost:
o	RMSE: 0.1934, R²: 0.1019 (underperformed)
Conclusion: Random Forest outperforms Linear Regression, while XGBoost performed poorly with the simplified implementation.

