# Insurance Fraud Detection Analytics
**Advanced Ensemble Learning & Imbalanced Data Handling**

## The Mission
To mitigate financial loss for insurers by identifying fraudulent claims. Fraud detection datasets are notoriously imbalanced (fraud is rare compared to legitimate claims), requiring advanced statistical sampling and modeling techniques to prevent the model from simply guessing "Not Fraud" every time.

## Technical Architecture
* **Data Balancing:** Engineered a solution for severe class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique) to generate synthetic examples of fraudulent claims.
* **Ensemble Modeling:** Developed a multi-layer **Stacked Generalization** model using `vecstack`. 
* **Base Models:** Combined the predictive power of **Random Forest**, **Gradient Boosting**, and **Decision Trees** to capture complex, non-linear fraud patterns.

## Key Metrics & Results
* **Performance:** The stacked ensemble model significantly outperformed individual classifiers in both Accuracy and Recall.
* **Validation:** Verified predictive stability and model capability through rigorous cross-validation and **ROC-AUC** analysis, proving the model's reliability in distinguishing subtle fraudulent activities.

## Skills Showcased
`Python` `Scikit-Learn` `SMOTE` `Ensemble Learning` `Gradient Boosting` `Imbalanced Data Analytics` `Fraud Detection`
