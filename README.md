<h1>Loan Default Prediction : Predicting whether a customer will default on a loan.</h1>
<b>Problem Statement:-</b>Lending Club is the world’s largest online marketplace connecting borrowers and investors. An inevitable outcome of lending is the default by borrowers. The idea of this tutorial is to create a predictive model that identifies applicants who are relatively risky for a loan.

<b>Approch</b>
<ul>
  <li>Engineered a new class of attributes known as Decayed Field variables and developed out-of-pattern variables on historical loan and bureau data to identify risky customers    and strengthen the underwriting process</li>
  <li>Performed missing value imputation using KNN-Imputer, implemented SMOTE boosting to oversample the minority class observations, and carried out Hyperparameter tuning using Bayesian optimization to come
up with the best model</li>
  
  <li>Obtained Model Reason Codes(MRCs) by leveraging the novel concept of SHAP values and SHAP charts such as summary, interaction, and force plots to come up with the best explanation for model predictions</li>
  
  <li>Developed an Xgboost model based on a binary classification model to predict loan defaulters and obtained the AUC-ROC score of 0.92 on validation data</li>

  </ul>
