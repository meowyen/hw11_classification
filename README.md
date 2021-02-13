# Homework 11: Classification

### Resources
- [Data](Resources/LoanStats_2019Q1.csv.zip)
- [Credit Risk Ensemble Notebook](credit_risk_ensemble.ipynb)
- [Credit Risk Resample Notebook](credit_risk_resampling.ipynb)

### Credit Risk Ensemble

This notebook compares two ensemble classifiers, Balanced Random Forest and Easy Ensemble. The Easy Ensemble classifier yielded a higher balanced accuracy score (0.931) compared to the Balanced Random Forest classifier (0.788). Additionally, the average recall score of Easy Ensemble (0.94) was also higher.

The precision for the high risk classification is very low (0.03 and 0.09) compared to the low risk classification (1.00). As a result, this model might be better predicting low risk applications.

### Credit Risk Resampling

This notebook compares the various resampling methods (oversample, undersampling, combination of both). Overall, the SMOTE resampling method resulted with a higher recall and balanced accuracy score when compared to the other methods.