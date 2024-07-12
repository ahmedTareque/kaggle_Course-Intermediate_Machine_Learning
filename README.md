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
  - Ordinal Encoding assigns each unique category a unique integer value(ex: 0,1,2,3,4,5). It doesn't increase the number the columns or even entries. It just replaces the value of the column with a unique integer value.
* One-Hot Encoding
  - One-Hot Encoding usually create a binary column indicating the presence (1) or absence (0) for each unique value from categorical column. Just imagine, each unique value from categorical column will be an individual column with just the value of 1 or 0. As an example, consider a dataframe containing 7 rows and one single column(categorical[which can be categorized easily]) with 3 unique entries. So, to get better MAE we can use One-hot encoding which will replace each unique category into a column with the value of either 1 or 0. For this example, we used to have 1 column with 3 unique value with 7 rows, So entries = 7×1=7. After using One-Hot encoding, we will have 3 columns and 7*3 = 21 entries.

## Certificate

