
Credit Risk Analysis Report

Overview of the Analysis: 
In this analysis, I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. The anaysis was divided into the following subsections:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Predict a Logistic Regression Model with Resampled Training Data
- Write a Credit Risk Analysis Report
Methods including `LogisticRegression`, `value_counts` were used

Results:

The accuracy for the Imbalanced data model is 94% (could be improved due to the data being imbalanced), while the accuracy for the OverSampled data model is 99%. The OverSampled data model is more reliable model when analysing data in this instance.

The precision score for the Imbalanced data model was 100% precise for healthy loan and 85% precise for high-risk loan when making predictions. On the other hand, The precision score for the OverSampled data model was 100% precise for healthy loan and 84% precise for high-risk loan when makeing predictions.


Summary: The Logistic Regression model with the OverSampled data should be chosen based its performance.