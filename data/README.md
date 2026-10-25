# Data

The dataset is not included in this repository.

Source: [Bank Customer Churn Modeling on Kaggle](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

Expected filename: `Churn.csv`.

The notebook currently attempts to load `/datasets/Churn.csv` first. If that file is unavailable, it downloads the dataset from the public course mirror defined in the data-loading cell. Therefore, an internet connection is required when the dataset is not available locally.

The source dataset must contain the following columns:

```text
RowNumber
CustomerId
Surname
CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Exited
```

The dataset is subject to the terms of its original provider and is intentionally excluded through `.gitignore`.
