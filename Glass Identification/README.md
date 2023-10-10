# Glass Identification Dataset
6 types of glass defined in terms of their oxide content `(i.e. Na, Fe, K, etc)` from USA Forensic Science Service.

Creators:
  - [B. German](https://unknown.org)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 214         | 9          | Numerical     | Categorical | false          |

| # | Attribute Name | Role     | Type        | Units                                 | Missing Values | Description      |
| - | -------------- | -------- | ----------- | ------------------------------------- | -------------- | ---------------- |
| 0 | RI             | Feature  | Numerical   |                                       | false          | refractive index |
| 1 | Na             | Feature  | Numerical   | weight percent in corresponding oxide | false          | Sodium           |
| 2 | Mg             | Feature  | Numerical   | weight percent in corresponding oxide | false          | Magnesium        |
| 3 | Al             | Feature  | Numerical   | weight percent in corresponding oxide | false          | Aluminum         |
| 4 | Si             | Feature  | Numerical   | weight percent in corresponding oxide | false          | Silicon          |
| 5 | K              | Feature  | Numerical   | weight percent in corresponding oxide | false          | Potassium        |
| 6 | Ca             | Feature  | Numerical   | weight percent in corresponding oxide | false          | Calcium          |
| 7 | Ba             | Feature  | Numerical   | weight percent in corresponding oxide | false          | Barium           |
| 8 | Fe             | Feature  | Numerical   | weight percent in corresponding oxide | false          | Iron             |
| 9 | class          | `Target` | Categorical |                                       | false          | glass type       |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name  |
| - | -------------- | ------------ | ---------------- |
| 9 | class          | 6            | 1, 2, 3, 5, 6, 7 |
```

## Some Samples
```
| # Sample | RI      | Na    | Mg   | Al   | Si    | K    | Ca    | Ba   | Fe   | class |
| -------- | ------- | ----- | ---- | ---- | ----- | ---- | ----- | ---- | ---- | ----- |
| 0        | 1.52101 | 13.64 | 4.49 | 1.10 | 71.78 | 0.06 | 8.75  | 0.00 | 0.00 | 1     |
| 1        | 1.51761 | 13.89 | 3.60 | 1.36 | 72.73 | 0.48 | 7.83  | 0.00 | 0.00 | 1     |
| 70       | 1.51574 | 14.86 | 3.67 | 1.74 | 71.87 | 0.16 | 7.36  | 0.00 | 0.12 | 2     |
| 71       | 1.51848 | 13.64 | 3.87 | 1.27 | 71.96 | 0.54 | 8.32  | 0.00 | 0.32 | 2     |
| 146      | 1.51769 | 13.65 | 3.66 | 1.11 | 72.77 | 0.11 | 8.60  | 0.00 | 0.00 | 3     |
| 147      | 1.51610 | 13.33 | 3.53 | 1.34 | 72.67 | 0.56 | 8.33  | 0.00 | 0.00 | 3     |
| 163      | 1.51514 | 14.01 | 2.68 | 3.50 | 69.89 | 1.68 | 5.87  | 2.20 | 0.00 | 5     |
| 164      | 1.51915 | 12.73 | 1.85 | 1.86 | 72.69 | 0.60 | 10.09 | 0.00 | 0.00 | 5     |
| 176      | 1.51905 | 14.00 | 2.39 | 1.56 | 72.37 | 0.00 | 9.57  | 0.00 | 0.00 | 6     |
| 177      | 1.51937 | 13.79 | 2.41 | 1.19 | 72.76 | 0.00 | 9.77  | 0.00 | 0.00 | 6     |
| 185      | 1.51131 | 13.69 | 3.20 | 1.81 | 72.81 | 1.76 | 5.43  | 1.19 | 0.00 | 7     |
| 186      | 1.51838 | 14.32 | 3.26 | 2.22 | 71.25 | 1.46 | 5.79  | 1.63 | 0.00 | 7     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/42/glass+identification](https://archive.ics.uci.edu/dataset/42/glass+identification) for more information.