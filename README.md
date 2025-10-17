# call_data_scoring_model

•	Problem Definition: Built a machine learning model to predict the likelihood of a call resulting in a sale, using real-world call center data enriched with geo and census features. Addressed a significantly imbalanced classification problem.
•	Data Processing & Analysis: Conducted EDA to assess feature distributions, missing values, and class imbalance. Cleaned and merged call logs with geo-location and demographic data (e.g., income, household size, health coverage).
•	Feature Engineering: Extracted time-based features (e.g., call hour, weekday/weekend), encoded categorical variabes (e.g., supplier, call period), and generated region-level aggregates from ZIP-based census data.
•	Model Development: Trained and compared several classifiers including XGBoost, LightGBM, and Logistic Regression. Used SMOTE to address class imbalance and stratified cross-validation for robust model evaluation.
•	Evaluation & Optimization: Evaluated models using ROC-AUC, F1-score, precision, and recall. Optimized hyperparameters using RandomizedSearchCV. Monitored prediction drift and planned for retraining using batch inference.
•	Results: Achieved strong predictive performance with balanced recall and precision. Designed a deployment-ready pipeline (batch scoring) and documented strategy for scaling and monitoring in a production environment.
