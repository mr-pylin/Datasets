# Palmer Penguins Dataset
The goal of palmerpenguins is to provide a great dataset for `data exploration` & `visualization`, as an alternative to `iris`.

Creators:
  - [Allison Horst](https://allisonhorst.com)
  - [Alison Hill](https://www.apreshill.com)
  - [Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php)

# More Details
| Associated Tasks | # Instances | # Features | Features Type          | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ---------------------- | ----------- | -------------- |
| Classification   | 344         | 7          | Numerical, Categorical | Categorical | true `19`      |

Missing Values are considered as `null` in the dataset.

| # | Attribute Name | Role     | Type        | Units | Missing Values | Description     |
| - | -------------- | -------- | ----------- | ----- | -------------- | --------------- |
| 0 | island         | Feature  | Categorical |       | false          |                 |
| 1 | bill-length    | Feature  | Numerical   | mm    | `true 2`       |                 |
| 2 | bill-depth     | Feature  | Numerical   | mm    | `true 2`       |                 |
| 3 | flipper-length | Feature  | Numerical   | mm    | `true 2`       |                 |
| 4 | body-mass      | Feature  | Numerical   | g     | `true 2`       |                 |
| 5 | sex            | Feature  | Categorical |       | `true 11`      |                 |
| 6 | year           | Feature  | Numerical   |       | false          | gregorian year  |
| 7 | class          | `Target` | Categorical |       | false          | penguin species |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name           |
| - | -------------- | ------------ | ------------------------- |
| 0 | island         | 3            | Torgersen, Biscoe, Dream  |
| 5 | sex            | 2            | male, female              |
| 7 | class          | 3            | Adelie, Gentoo, Chinstrap |
```

## Some Samples
```
| # Sample | island    | bill-length | bill-depth | flipper-length | body-mass | sex    | year | class     |
| -------- | --------- | ----------- | ---------- | -------------- | --------- | ------ | ---- | --------- |
| 0        | Torgersen | 39.1        | 18.7       | 181            | 3750      | male   | 2007 | Adelie    |
| 20       | Biscoe    | 37.8        | 18.3       | 174            | 3400      | female | 2007 | Adelie    |
| 152      | Biscoe    | 46.1        | 13.2       | 211            | 4500      | female | 2007 | Gentoo    |
| 153      | Biscoe    | 50          | 16.3       | 230            | 5700      | male   | 2007 | Gentoo    |
| 276      | Dream     | 46.5        | 17.9       | 192            | 3500      | female | 2007 | Chinstrap |
| 277      | Dream     | 50          | 19.5       | 196            | 3900      | male   | 2007 | Chinstrap |
```
<div align='center'><img src="./demo/demo1.png" alt="demo"></div>
<div align='center'><img src="./demo/demo2.png" alt="demo"></div>

# License
This dataset is licensed under a [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0) (`CC0 1.0`) license.  
TL;DR: It enables creators to waive all copyright and related rights worldwide (the creator dedicates their work to the public domain).

# Credit
The official website of the `Palmer Penguins` dataset: [allisonhorst.github.io/palmerpenguins/](https://allisonhorst.github.io/palmerpenguins).