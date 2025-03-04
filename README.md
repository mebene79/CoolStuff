Different ways to handle missing data in a dataset where all the features are categorical including the target.

We explore diffrent ways to handle missing data in the Mushroom Data Set https://archive.ics.uci.edu/ml/datasets/mushroom

In this Dataset the features and target are all categorical and one feature has misssing data . We explore ddifferent ways to deal with the missing information .

1) First determine if the missing data is informative e.g. missing because of some underlying reason related to the target. If it's the case,then creating a new category like "Missing" might capture that.
   
2) Imputation ,like replacing the missing values by the mode but choosing this option depends on whether or not the missingness is related to the target.
   
3) Model-based imputation, like using a Random Forest to predict missing values
   
4) Deleting all rows with missing values.
   
5) Use Models that Handle Missing Data Natively(e.g., LightGBM, CatBoost)
