# Credit Risk Modeling

## Credit Risk Modeling Project: German Credit Data
This project explores credit risk modeling using the German Credit dataset. The goal was to build a model that distinguishes between "good" and "bad" credit risks to aid banks and lending institutions. Below, I present my approach, findings, and next steps.

## 1. Data Preparation and Exploration
Starting with data inspection, I reviewed both categorical and numerical features, alongside the target variable `Credit_risk` indicating credit status. Key observations include:

- **Categorical Features**: Variables like `Purpose`, `Housing`, and `Employment_status`, which reflect financial and personal details.
- **Numerical Features**: Variables such as `Duration_in_month`, `Credit_amount`, and `Age_in_years`, representing loan terms, amounts, and demographics.

### Example Finding
Higher-risk loans were more frequent in the "new car" category, while "furniture" loans often had good credit outcomes.

_Image Placeholder: Data Preparation and Exploration_

## 2. Bivariate Analysis
To understand feature relationships with `Credit_risk`, I conducted bivariate analysis:

- **Categorical Analysis**: Chi-square tests revealed significant links between `Employment_status`, `Credit_history`, and credit risk levels.
- **Numerical Analysis**: Box plots showed that higher `Credit_amount` was associated with "bad" credit risks.

_Image Placeholder: Bivariate Analysis_

## 3. Feature Engineering
Based on insights from bivariate analysis, I engineered features to add value to the dataset:

- **Binning**: Grouped `Age_in_years` and `Credit_amount` into meaningful ranges.
- **Interaction Features**: Combined features like `Employment_status` and `Credit_history` for joint effects.
- **Encoding**: Applied one-hot encoding to transform categorical features for modeling.

## 4. Outlier Detection
Using the Interquartile Range (IQR) method, I identified outliers that could impact model stability:

- **Credit_amount**: Higher values showed a link with "bad" credit risks.
- **Duration_in_month**: Extremely short or long durations were observed in both credit risk categories.

### Next Steps
I plan to cap or transform certain features to limit outlier influence without data loss.

## 5. Addressing Class Imbalance
With a target variable imbalance favoring "good" credit cases, I plan to use SMOTE (Synthetic Minority Over-sampling Technique) to balance the classes and improve model learning.

_Image Placeholder: Addressing Class Imbalance_

## 6. Modeling and Evaluation (Upcoming)
Next steps include training and evaluating models to predict credit risk. The planned approach includes:

- **Model Selection**: Testing logistic regression, decision trees, and ensemble methods, with an emphasis on minority class accuracy.
- **Evaluation**: Assessing each model using metrics such as precision, recall, and ROC-AUC.

## Conclusion
This project has been an in-depth exploration of credit risk modeling. With model training underway, I look forward to using these engineered features to build a reliable predictive model that supports better credit decision-making for financial institutions.
