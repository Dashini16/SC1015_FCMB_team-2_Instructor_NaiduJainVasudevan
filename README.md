# SC1015_FCMB_team-2_Instructor_NaiduJainVasudevan

Bitcoin Price Prediction Models

Introduction:
This project aims to predict Bitcoin price trends over an 8-year period using various machine learning models. The models evaluated include Linear Regression, Polynomial Regression, Ridge Regression, Decision Tree Classifier, Naive Bayes, Support Vector Machine (SVM), and Long Short-Term Memory (LSTM) neural networks. Evaluation is based on metrics such as Root Mean Squared Error (RMSE), Mean Squared Error (MSE), Mean Absolute Error (MAE), Explained Variance, R-squared (R2), Mean Gross Error (MGD), and Mean Percentage Difference (MPD).

Data Preprocessing:
The following preprocessing steps were performed on the dataset before training the models:

1. Data Cleaning:
   - Missing values were handled by either imputation or removal, depending on the amount of missing data and its impact on the analysis.
   - Outliers were identified and treated using statistical methods or domain knowledge.

2. Feature Scaling:
   - Numeric features were scaled to a standard range using techniques such as Min-Max scaling or Standard scaling to ensure that all features contribute equally to the model.

3. Data Splitting:
   - The dataset was split into training and testing sets to train the models on a portion of the data and evaluate their performance on unseen data.

Overview of Models:
1. Linear Regression
2. Polynomial Regression
3. Ridge Regression
4. Decision Tree Classifier
5. Naive Bayes
6. Support Vector Machine (SVM)
7. Long Short-Term Memory (LSTM)

Model Performance:
The performance of each model is evaluated based on its ability to accurately predict Bitcoin price trends. Key evaluation metrics include RMSE, MSE, MAE, Explained Variance, R2, MGD, and MPD. Here's a summary of the findings:

- Linear Regression, Polynomial Regression, and Ridge Regression demonstrate high accuracy and strong predictive power, capturing the underlying patterns in the data effectively.
- Decision Tree Classifier performs relatively poorly compared to other models, indicating limitations in capturing the complex relationships in the data.
- Naive Bayes shows subpar performance, with high MPD values indicating significant deviations from actual values.
- SVM achieves high accuracy and generalization capability, making it a viable option for Bitcoin price prediction.
- LSTM emerges as the most effective model, leveraging its ability to capture temporal dependencies and handle non-linear relationships in the data.

Conclusion:
Based on the evaluation of various machine learning models, LSTM stands out as the preferred choice for predicting Bitcoin price trends over an 8-year period. Its ability to capture temporal dependencies, handle large amounts of data, and learn non-linear relationships makes it well-suited for this challenging task. However, other models like Linear Regression, Polynomial Regression, and Ridge Regression also demonstrate strong performance and can be considered depending on specific requirements and constraints.

Kaggle Dataset:https://www.kaggle.com/datasets/aspillai/bitcoin-price-trends-with-indicators-8-years?resource=download

Our Contributions:
Ishita Chetan Jain: Presentor, Slides, Script and Classification Models(including analysis) and analysis for 2020 to 2022.
Aditi Vasudevan: Presentor, Slides, Script and Regression Models(including analysis) and analysis for 2023 to Overall Analysis.
Dashini Naidu: Slides, LSTM, Analysis for 2015 to 2019, EDA coding, Evaluation, Slides, Data Preprocessing.
