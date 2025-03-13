# Credit-Risk-Classification

# Loan Default Prediction using Logistic Regression

## Project Overview
This project analyzes financial data to predict whether a borrower will default on a loan. Using machine learning techniques, we built a classification model to assess loan risk.

## Dataset Information
The dataset contains financial variables such as:
- **Loan Size**
- **Interest Rate**
- **Borrower Income**
- **Debt-to-Income Ratio**
- **Number of Accounts**
- **Derogatory Marks**
- **Total Debt**
- **Loan Status** (Target variable: `0 = Not Defaulted`, `1 = Defaulted`)

## Machine Learning Workflow
1. **Data Preparation**  
   - Separated features (`X`) and target (`y`).
   - Split data into training (80%) and testing (20%) sets.

2. **Model Training**  
   - Used **Logistic Regression** with `random_state=1` for consistency.

3. **Model Evaluation**  
   - **Confusion Matrix**: Assessed correct and incorrect predictions.
   - **Classification Report**:
     - **Accuracy:** 99%
     - **Precision for Defaults (`1`)**: 86%
     - **Recall for Defaults (`1`)**: 91%

## Performance Considerations
- The model performed well overall, with high accuracy and recall.
- If minimizing financial risk is the priority, **recall for defaults (`1`)** is crucial.
- Future improvements could include testing alternative models like **Random Forest** or **Decision Trees**.

## Next Steps
- Optimize the model using hyperparameter tuning.
- Experiment with different machine learning algorithms.
- Conduct feature engineering to improve prediction accuracy.

