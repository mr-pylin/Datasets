# White Wine Quality Dataset
This dataset is related to `white` vinho verde wine samples, from the north of Portugal.  
The goal is to score wine quality (from `0` to `10`) based on physicochemical tests.

Creators:
  - [Paulo Cortez](https://pt.linkedin.com/in/paulocortez)
  - [A. Cerdeira](https://www.scopus.com/authid/detail.uri?authorId=57201838996)
  - [F. Almeida](https://unknown.org)
  - [T. Matos](https://www.researchgate.net/profile/Telmo-Matos)
  - [J. Reis](https://www.researchgate.net/profile/Jose-Reis-6)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 4898        | 9          | Numerical     | Categorical | false          |

| #  | Attribute Name       | Role     | Type        | Units | Missing Values | Description |
| -- | -------------------- | -------- | ----------- | ----- | -------------- | ----------- |
| 0  | fixed-acidity        | Feature  | Numerical   |       | false          |             |
| 1  | volatile-acidity     | Feature  | Numerical   |       | false          |             |
| 2  | citric-acid          | Feature  | Numerical   |       | false          |             |
| 3  | residual-sugar       | Feature  | Numerical   |       | false          |             |
| 4  | chlorides            | Feature  | Numerical   |       | false          |             |
| 5  | free-sulfur-dioxide  | Feature  | Numerical   |       | false          |             |
| 6  | total-sulfur-dioxide | Feature  | Numerical   |       | false          |             |
| 7  | density              | Feature  | Numerical   |       | false          |             |
| 8  | pH                   | Feature  | Numerical   |       | false          |             |
| 9  | sulphates            | Feature  | Numerical   |       | false          |             |
| 10 | alcohol              | Feature  | Numerical   |       | false          |             |
| 11 | class                | `Target` | Categorical |       | false          |             |

## Categorical Attributes
`Note:` "Unavailable Categories", mean that there are no instances in this dataset assigned to that category [but that categories are mentioned in the original reference].
```
| #  | Attribute Name | # Categories | Available Categories | Unavailable Categories |
| -- | -------------- | ------------ | -------------------- | ---------------------- |
| 11 | class          | 11           | 3, 4, 5, 6, 7, 8, 9  | 0, 1, 2, 10            |
```

## Some Samples
```
| # Sample | fixed-acidity | volatile-acidity | citric-acid | residual-sugar | chlorides | free-sulfur-dioxide | total-sulfur-dioxide | density | pH   | sulphates | alcohol | class |
| -------- | ------------- | ---------------- | ----------- | -------------- | --------- | ------------------- | -------------------- | ------- | ---- | --------- | ------- | ----- |
| 251      | 8.5           | 0.26             | 0.21        | 16.2           | 0.074     | 41                  | 197                  | 0.998   | 3.02 | 0.5       | 9.8     | 3     |
| 259      | 5.8           | 0.36             | 0.38        | 0.9            | 0.037     | 3                   | 75                   | 0.9904  | 3.28 | 0.34      | 11.4    | 4     |
| 261      | 6.9           | 0.29             | 0.4         | 19.45          | 0.043     | 36                  | 156                  | 0.9996  | 2.93 | 0.47      | 8.9     | 5     |
| 263      | 7.2           | 0.29             | 0.4         | 13.6           | 0.045     | 66                  | 231                  | 0.9977  | 3.08 | 0.59      | 9.6     | 6     |
| 279      | 7             | 0.3              | 0.49        | 4.7            | 0.036     | 17                  | 105                  | 0.9916  | 3.26 | 0.68      | 12.4    | 7     |
| 280      | 7             | 0.24             | 0.36        | 2.8            | 0.034     | 22                  | 112                  | 0.99    | 3.19 | 0.38      | 12.6    | 8     |
| 774      | 9.1           | 0.27             | 0.45        | 10.6           | 0.035     | 28                  | 124                  | 0.997   | 3.2  | 0.46      | 10.4    | 9     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/186/wine+quality](https://archive.ics.uci.edu/dataset/186/wine+quality) for more information.