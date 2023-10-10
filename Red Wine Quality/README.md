# Red Wine Quality Dataset
This dataset is related to `red` vinho verde wine samples, from the north of Portugal.  
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
| Classification   | 1599        | 9          | Numerical     | Categorical | false          |

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
| 11 | class          | 11           | 3, 4, 5, 6, 7, 8     | 0, 1, 2, 9, 10         |
```

## Some Samples
```
| # Sample | fixed-acidity | volatile-acidity | citric-acid | residual-sugar | chlorides | free-sulfur-dioxide | total-sulfur-dioxide | density | pH   | sulphates | alcohol | class |
| -------- | ------------- | ---------------- | ----------- | -------------- | --------- | ------------------- | -------------------- | ------- | ---- | --------- | ------- | ----- |
| 459      | 11.6          | 0.58             | 0.66        | 2.2            | 0.074     | 10                  | 47                   | 1.0008  | 3.25 | 0.57      | 9       | 3     |
| 573      | 10.5          | 0.59             | 0.49        | 2.1            | 0.07      | 14                  | 47                   | 0.9991  | 3.3  | 0.56      | 9.6     | 4     |
| 577      | 8.8           | 0.44             | 0.49        | 2.8            | 0.083     | 18                  | 111                  | 0.9982  | 3.3  | 0.6       | 9.5     | 5     |
| 579      | 10.6          | 0.31             | 0.49        | 2.2            | 0.063     | 18                  | 40                   | 0.9976  | 3.14 | 0.51      | 9.8     | 6     |
| 583      | 12            | 0.28             | 0.49        | 1.9            | 0.074     | 10                  | 21                   | 0.9976  | 2.98 | 0.66      | 9.9     | 7     |
| 588      | 5             | 0.42             | 0.24        | 2              | 0.06      | 19                  | 50                   | 0.9917  | 3.72 | 0.74      | 14      | 8     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/186/wine+quality](https://archive.ics.uci.edu/dataset/186/wine+quality) for more information.