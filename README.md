# Kaggle Course


## Intermediate Machine Learning

Handle missing values, non-numeric values, data leakage, and more.

[Course Link](https://www.kaggle.com/learn/intermediate-machine-learning)

### Lessons

* Introduction
* Missing Values
* Categorical Variables
* Pipelines
* Cross-Validation
* XGBoost
* Data Leakage

Instructor
[Alexis Cook](https://www.kaggle.com/alexisbcook)

### KeyNotes [Few gists to remember from this lessons]

* Imputation
  - Usually we can use `SimpleImputer` (`from sklearn.impute import SimpleImputer`) to replace missing values with the mean value along each column rather than dropping the same columns from training and validation sets. It has lower MAE(Mean Absolute Error) and performs better. Even we can track the columns which values were imputed.
* Ordinal Encoding
  - Ordinal Encoding assigns each unique category a unique integer value(ex: 0,1,2,3,4,5). It doesn't increase the number the columns. It just replace the value of the column with that unique integer value.
* One-Hot Encoding
  - One-Hot Encoding usually create a binary column indicating the presence (1) or absence (0) for each unique category. As an example, consider a dataset containing 7 rows and one categorical column with 3 unique entries. 

## Certificate

