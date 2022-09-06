# ATP Tennis Match Prediction
*Disclaimer: this notebook is created for academic purposes and has no affiliation with any institution*

- Objective: To build a classification machine learning model to predict ATP match result
- Data Source: ATP match data 2001 to 2021 is sourced from https://github.com/JeffSackmann/tennis_atp
- Model Input: Features used are related to player's past performances (past ranks, rank point, etc.) and player's characteristics
- Model Output: Binary value explaining the winning result where '0' if Player 1 wins and '1' if Player 2 wins
- List of models trained: 
  1. Logistic Regression
  2. Decision Tree Classifier
  3. K-Nearest Neighbors Classifier
  4. Gaussian Naive Bayes
  5. SGD Classifier
  6. Neural Network Classifier (Multi-Layer Perceptron)
  7. Random Forest Classifier
  8. Ensemble Method (Gradient Boosting Classifier)
  9. Ensemble Method (Voting Classifier
  10. Ensemble Method (XGBoost Classfier)
- Evaluation Metrics: Accuracy score and Recall (use classification report and confusion matrix)
- Feature Importance using SHAP package
