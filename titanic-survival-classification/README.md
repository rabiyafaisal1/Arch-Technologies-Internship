# Titanic Survival Classification

Predicts whether a Titanic passenger survived using Logistic Regression, based on age, sex, ticket class, and fare.

**Result:** 81% accuracy on the test set

**Key finding:** Sex and passenger class were by far the strongest predictors — reflecting the historical "women and children first" evacuation priority and unequal lifeboat access across ticket classes.

**Tools:** Python, pandas, scikit-learn, matplotlib, Google Colab

**Workflow:** data cleaning (missing Age/Embarked/Cabin) → encoding categorical variables → train/test split → Logistic Regression → evaluation (accuracy, confusion matrix, classification report) → feature importance visualization
