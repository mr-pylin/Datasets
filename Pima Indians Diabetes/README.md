# Pima Indians Diabetes Dataset
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.  
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.  
all patients here are females at least 21 years old of Pima Indian heritage.

Creators:
  - [Unknown](https://www.unknown.org)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 768         | 8          | Numerical     | Categorical | false          |

| # | Attribute Name           | Role     | Type        | Units   | Missing Values | Description                                                              |
| - | ------------------------ | -------- | ----------- | ------- | -------------- | ------------------------------------------------------------------------ |
| 0 | pregnancies              | Feature  | Numerical   |         | false          | Number of times pregnant                                                 |
| 1 | glucose                  | Feature  | Numerical   |         | false          | Plasma glucose concentration a 2 hours in an oral glucose tolerance test |
| 2 | bloodpressure            | Feature  | Numerical   | mm Hg   | false          | Diastolic blood pressure                                                 |
| 3 | skinthickness            | Feature  | Numerical   | mm      | false          | Triceps skin fold thickness                                              |
| 4 | insulin                  | Feature  | Numerical   | mu U/ml | false          | 2-Hour serum insulin                                                     |
| 5 | bmi                      | Feature  | Numerical   | kg/m^2  | false          | Body mass index (weight/(height)^2)                                      |
| 6 | diabetespedigreefunction | Feature  | Numerical   |         | false          | Diabetes pedigree function                                               |
| 7 | age                      | Feature  | Numerical   |         | false          | Age (years)                                                              |
| 8 | class                    | `Target` | Categorical |         | false          | has diabete                                                              |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name                        |
| - | -------------- | ------------ | -------------------------------------- |
| 8 | class          | 2            | 0(do not have diabete), 1(has diabete) |
```

## Some Samples
```
| # Sample | pregnancies | glucose | bloodpressure | skinthickness | insulin | bmi  | diabetespedigreefunction | age | class |
| -------- | ----------- | ------- | ------------- | ------------- | ------- | ---- | ------------------------ | --- | ----- |
| 0        | 6           | 148     | 72            | 35            | 0       | 33.6 | 0.627                    | 50  | 1     |
| 1        | 1           | 85      | 66            | 29            | 0       | 26.6 | 0.351                    | 31  | 0     |
| 2        | 8           | 183     | 64            | 0             | 0       | 23.3 | 0.672                    | 32  | 1     |
| 3        | 1           | 89      | 66            | 23            | 94      | 28.1 | 0.167                    | 21  | 0     |
| 4        | 0           | 137     | 40            | 35            | 168     | 43.1 | 2.288                    | 33  | 1     |
| 5        | 5           | 116     | 74            | 0             | 0       | 25.6 | 0.201                    | 30  | 0     |
```

# License
This dataset is licensed under a [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0) (`CC0 1.0`) license.  
TL;DR: It enables creators to waive all copyright and related rights worldwide (the creator dedicates their work to the public domain).

# Credit
Visit [kaggle.com/datasets/uciml/pima-indians-diabetes-database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) for more information.