**MPG Displacement Prediction** (Decision Tree vs Random Forest)

A hands-on ML project predicting a car's engine displacement from its specs (mpg, cylinders, horsepower, weight, acceleration, model year) using seaborn's `mpg` dataset.

Built to practice the core ML workflow from Kaggle's Intro to Machine Learning course: data cleaning → train/validation split → baseline Decision Tree → hyperparameter tuning → Random Forest comparison.

**Results:**
- Decision Tree (tuned): MAE ~20.2
- Random Forest (default): MAE ~17.0

**Takeaway:** 
Random Forests reduce overfitting by averaging many trees, outperforming a single tuned decision tree with less manual effort.

**Stack:** 
python, pandas, seaborn, scikit-learn
