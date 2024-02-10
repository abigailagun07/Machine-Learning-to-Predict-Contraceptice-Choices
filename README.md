# Machine-Learning-to-Predict-Contraceptive-Choices
This project investigates contraceptive method choices among Indonesian women, utilizing a subset of data from the National Indonesia Contraceptive Prevalence Survey. The analysis focuses on understanding how demographic and socio-economic factors influence contraceptive method selection, aiming to support policymakers in enhancing family planning programs.

## Data Description
The dataset includes attributes like age, education, number of children, and employment status, among others, with the target variable being the choice of contraceptive method: No use, Long term, or Short term.

## Methodology
Data Preprocessing: Initial data cleaning and transformation to prepare for analysis.
Exploratory Data Analysis (EDA): Employed various graphical techniques to gain insights into the data distribution and relationships between variables.
Modeling: Explored classification algorithms such as SVM, Decision Trees, and Random Forest to predict contraceptive method choices.
Evaluation: Model performance was assessed using metrics like accuracy, precision, recall, and F1 score, alongside cross-validation for robustness.

## Key Insights
The analysis revealed significant factors influencing contraceptive choices, such as education levels, number of children, and living standards.
Class imbalance was addressed using SMOTE to ensure model fairness and accuracy.

## Tools and Technologies
Languages: Python
Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, imblearn
