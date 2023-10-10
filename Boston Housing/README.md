# Boston Housing Dataset
The famous Boston Housing Dataset is used in many tutorials, examples, and books.  
This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts.

Creators:
  - [David Harrison](https://www.linkedin.com/in/hdahme)
  - [Daniel L. Rubinfeld](https://en.wikipedia.org/wiki/Daniel_L._Rubinfeld)

# More Details
| Associated Tasks | # Instances | # Features | Features Type          | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ---------------------- | ----------- | -------------- |
| Regression       | 506         | 13         | Numerical, Categorical | Numerical   | false          |

| #  | Attribute Name | Role     | Type        | Units  | Missing Values | Description                                                      |
| -- | -------------- | -------- | ----------- | ------ | -------------- | ---------------------------------------------------------------- |
| 0  | crim           | Feature  | Numerical   |        | false          | per capita crime rate by town                                    |
| 1  | zn             | Feature  | Numerical   | sq.ft. | false          | proportion of residential land zoned for lots over 25,000 sq.ft. |
| 2  | indus          | Feature  | Numerical   |        | false          | proportion of non-retail business acres per town                 |
| 3  | chas           | Feature  | Categorical |        | false          | Charles River dummy variable                                     |
| 4  | nox            | Feature  | Numerical   |        | false          | nitric oxides concentration (parts per 10 million)               |
| 5  | rm             | Feature  | Numerical   |        | false          | average number of rooms per dwelling                             |
| 6  | age            | Feature  | Numerical   |        | false          | proportion of owner-occupied units built prior to 1940           |
| 7  | dis            | Feature  | Numerical   |        | false          | weighted distances to five Boston employment centres             |
| 8  | rad            | Feature  | Numerical   |        | false          | index of accessibility to radial highways                        |
| 9  | tax            | Feature  | Numerical   | $      | false          | full-value property-tax rate per $10,000                         |
| 10 | ptratio        | Feature  | Numerical   |        | false          | pupil-teacher ratio by town                                      |
| 11 | b              | Feature  | Numerical   |        | false          | 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town   |
| 12 | lstat          | Feature  | Numerical   |        | false          | % lower status of the population                                 |
| 13 | medv           | `Target` | Categorical | $      | false          | Median value of owner-occupied homes in $1000's                  |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name                        |
| - | -------------- | ------------ | -------------------------------------- |
| 3 | chas           | 2            | 1(if tract bounds river), 0(otherwise) |
```

## Some Samples
```
| # Sample | crim    | zn    | indus | chas | nox    | rm     | age   | dis    | rad | tax   | ptratio | b      | lstat | medv  |
| -------- | ------- | ----- | ----- | ---- | ------ | ------ | ----- | ------ | --- | ----- | ------- | ------ | ----- | ----- |
| 0        | 0.00632 | 18.00 | 2.310 | 0    | 0.5380 | 6.5750 | 65.20 | 4.0900 | 1   | 296.0 | 15.30   | 396.90 | 4.98  | 24.00 |
| 1        | 0.02731 | 0.00  | 7.070 | 0    | 0.4690 | 6.4210 | 78.90 | 4.9671 | 2   | 242.0 | 17.80   | 396.90 | 9.14  | 21.60 |
| 2        | 0.02729 | 0.00  | 7.070 | 0    | 0.4690 | 7.1850 | 61.10 | 4.9671 | 2   | 242.0 | 17.80   | 392.83 | 4.03  | 34.70 |
| 3        | 0.03237 | 0.00  | 2.180 | 0    | 0.4580 | 6.9980 | 45.80 | 6.0622 | 3   | 222.0 | 18.70   | 394.63 | 2.94  | 33.40 |
| 4        | 0.06905 | 0.00  | 2.180 | 0    | 0.4580 | 7.1470 | 54.20 | 6.0622 | 3   | 222.0 | 18.70   | 396.90 | 5.33  | 36.20 |
```

# License
This dataset is licensed under a [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0) (`CC0 1.0`) license.  
TL;DR: It enables creators to waive all copyright and related rights worldwide (the creator dedicates their work to the public domain).

# Credit
The official website of the `Boston Housing` dataset: [www.cs.toronto.edu/~delve/data/boston](https://www.cs.toronto.edu/~delve/data/boston).