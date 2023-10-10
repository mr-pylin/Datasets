# Abalone Dataset
Predict the age of abalone from physical measurements.  
Note: The number of rings tell us about the age of abalones.

Creators:
  - [Warwick Nash](https://unknown.org)
  - [Tracy Sellers](https://unknown.org)
  - [Simon Talbot](https://unknown.org)
  - [Andrew Cawthorn](https://unknown.org)
  - [Wes Ford](https://unknown.org)

# More Details
| Associated Tasks             | # Instances | # Features | Features Type              | Class Type  | Missing Values |
| ---------------------------- | ----------- | ---------- | -------------------------- | ----------- | -------------- |
| Classification, Regression   | 4177        | 8          | Categorical, Numerical     | Numerical   | false          |

| # | Attribute Name | Role     | Type        | Units | Missing Values | Description                 |
| - | -------------- | -------- | ----------- | ----- | -------------- | --------------------------- |
| 0 | sex            | Feature  | Categorical |       | false          | gender of abalones          |
| 1 | length         | Feature  | Numerical   | mm    | false          | Longest shell measurement   |
| 2 | diameter       | Feature  | Numerical   | mm    | false          | perpendicular to length     |
| 3 | height         | Feature  | Numerical   | mm    | false          | with meat in shell          |
| 4 | whole_weight   | Feature  | Numerical   | grams | false          | whole abalone               |
| 5 | shucked_weight | Feature  | Numerical   | grams | false          | weight of meat              |
| 6 | viscera_weight | Feature  | Numerical   | grams | false          | gut weight (after bleeding) |
| 7 | shell_weight   | Feature  | Numerical   | grams | false          | after being dried           |
| 8 | rings          | `Target` | Numerical   |       | false          | +1.5 gives the age in years |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name               |
| - | -------------- | ------------ | ----------------------------- |
| 0 | sex            | 3            | M(Male), F(Female), I(Infant) |
```

## Some Samples
```
| # Sample | sex | length | diameter | height | whole_weight | shucked_weight | viscera_weight | shell_weight | rings |
| -------- | --- | ------ | -------- | ------ | ------------ | -------------- | -------------- | ------------ | ----- |
| 0        | M   | 0.455  | 0.365    | 0.095  | 0.514        | 0.2245         | 0.101          | 0.15         | 15    |
| 1        | M   | 0.35   | 0.265    | 0.09   | 0.2255       | 0.0995         | 0.0485         | 0.07         | 7     |
| 2        | F   | 0.53   | 0.42     | 0.135  | 0.677        | 0.2565         | 0.1415         | 0.21         | 9     |
| 3        | M   | 0.44   | 0.365    | 0.125  | 0.516        | 0.2155         | 0.114          | 0.155        | 10    |
| 4        | I   | 0.33   | 0.255    | 0.08   | 0.205        | 0.0895         | 0.0395         | 0.055        | 7     |
| 5        | I   | 0.425  | 0.3      | 0.095  | 0.3515       | 0.141          | 0.0775         | 0.12         | 8     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/1/abalone](https://archive.ics.uci.edu/dataset/1/abalone) for more information.