# Breast Cancer Wisconsin
Diagnostic Wisconsin Breast Cancer Database.

Creators:
  - [William Wolberg](https://scholar.google.com/citations?user=R-kw9JYAAAAJ&hl=en)
  - [Olvi Mangasarian](https://scholar.google.com/citations?user=OkJ1G8YAAAAJ&hl=en)
  - [Nick Street](https://scholar.google.com/citations?user=-kKtBb8AAAAJ&hl=en)
  - [W. Street](https://https://unknown.org)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 569         | 30         | Numerical     | Categorical | false          |

| #  | Attribute Name     | Role     | Type        | Units | Missing Values | Description                                              |
| -- | ------------------ | -------- | ----------- | ----- | -------------- | -------------------------------------------------------- |
| 0  | radius1            | Feature  | Numerical   |       | false          | mean of distances from center to points on the perimeter |
| 1  | texture1           | Feature  | Numerical   |       | false          | standard deviation of gray-scale values                  |
| 2  | perimeter1         | Feature  | Numerical   |       | false          |                                                          |
| 3  | area1              | Feature  | Numerical   |       | false          |                                                          |
| 4  | smoothness1        | Feature  | Numerical   |       | false          | local variation in radius lengths                        |
| 5  | compactness1       | Feature  | Numerical   |       | false          | perimeter^2 / area - 1.0                                 |
| 6  | concavity1         | Feature  | Numerical   |       | false          | severity of concave portions of the contour              |
| 7  | concave-points1    | Feature  | Numerical   |       | false          | number of concave portions of the contour                |
| 8  | symmetry1          | Feature  | Numerical   |       | false          |                                                          |
| 9  | fractal-dimension1 | Feature  | Numerical   |       | false          | "coastline approximation" - 1                            |
| 10 | radius2            | Feature  | Numerical   |       | false          | mean of distances from center to points on the perimeter |
| 11 | texture2           | Feature  | Numerical   |       | false          | standard deviation of gray-scale values                  |
| 12 | perimeter2         | Feature  | Numerical   |       | false          |                                                          |
| 13 | area2              | Feature  | Numerical   |       | false          |                                                          |
| 14 | smoothness2        | Feature  | Numerical   |       | false          | local variation in radius lengths                        |
| 15 | compactness2       | Feature  | Numerical   |       | false          | perimeter^2 / area - 1.0                                 |
| 16 | concavity2         | Feature  | Numerical   |       | false          | severity of concave portions of the contour              |
| 17 | concave-points2    | Feature  | Numerical   |       | false          | number of concave portions of the contour                |
| 18 | symmetry2          | Feature  | Numerical   |       | false          |                                                          |
| 19 | fractal-dimension2 | Feature  | Numerical   |       | false          | "coastline approximation" - 1                            |
| 20 | radius3            | Feature  | Numerical   |       | false          | mean of distances from center to points on the perimeter |
| 21 | texture3           | Feature  | Numerical   |       | false          | standard deviation of gray-scale values                  |
| 22 | perimeter3         | Feature  | Numerical   |       | false          |                                                          |
| 23 | area3              | Feature  | Numerical   |       | false          |                                                          |
| 24 | smoothness3        | Feature  | Numerical   |       | false          | local variation in radius lengths                        |
| 25 | compactness3       | Feature  | Numerical   |       | false          | perimeter^2 / area - 1.0                                 |
| 26 | concavity3         | Feature  | Numerical   |       | false          | severity of concave portions of the contour              |
| 27 | concave-points3    | Feature  | Numerical   |       | false          | number of concave portions of the contour                |
| 28 | symmetry3          | Feature  | Numerical   |       | false          |                                                          |
| 29 | fractal-dimension3 | Feature  | Numerical   |       | false          | "coastline approximation" - 1                            |
| 30 | class              | `Target` | Categorical |       | false          | cancer type                                              |

## Categorical Attributes
```
| #  | Attribute Name | # Categories | Categories Name         |
| -- | -------------- | ------------ | ----------------------- |
| 30 | class          | 2            | M(malignant), B(benign) |
```

## Some Samples
```
| # Sample | radius1 | texture1 | perimeter1 | area1  | smoothness1 | compactness1 | concavity1 | concave-points1 | symmetry1 | fractal-dimension1 | radius2 | texture2 | perimeter2 | area2 | smoothness2 | compactness2 | concavity2 | concave-points2 | symmetry2 | fractal-dimension2 | radius3 | texture3 | perimeter3 | area3  | smoothness3 | compactness3 | concavity3 | concave-points3 | symmetry3 | fractal-dimension3 | class |
| -------- | ------- | -------- | ---------- | ------ | ----------- | ------------ | ---------- | --------------- | --------- | ------------------ | ------- | -------- | ---------- | ----- | ----------- | ------------ | ---------- | --------------- | --------- | ------------------ | ------- | -------- | ---------- | ------ | ----------- | ------------ | ---------- | --------------- | --------- | ------------------ | ----- |
| 0        | 17.99   | 10.38    | 122.8      | 1001.0 | 0.1184      | 0.2776       | 0.3001     | 0.1471          | 0.2419    | 0.07871            | 1.095   | 0.9053   | 8.589      | 153.4 | 0.006399    | 0.04904      | 0.05373    | 0.01587         | 0.03003   | 0.006193           | 25.38   | 17.33    | 184.6      | 2019.0 | 0.1622      | 0.6656       | 0.7119     | 0.2654          | 0.4601    | 0.1189             | M     |
| 1        | 20.57   | 17.77    | 132.9      | 1326.0 | 0.08474     | 0.07864      | 0.0869     | 0.07017         | 0.1812    | 0.05667            | 0.5435  | 0.7339   | 3.398      | 74.08 | 0.005225    | 0.01308      | 0.0186     | 0.0134          | 0.01389   | 0.003532           | 24.99   | 23.41    | 158.8      | 1956.0 | 0.1238      | 0.1866       | 0.2416     | 0.186           | 0.275     | 0.08902            | M     |
| 19       | 13.54   | 14.36    | 87.46      | 566.3  | 0.09779     | 0.08129      | 0.06664    | 0.04781         | 0.1885    | 0.05766            | 0.2699  | 0.7886   | 2.058      | 23.56 | 0.008462    | 0.0146       | 0.02387    | 0.01315         | 0.0198    | 0.0023             | 15.11   | 19.26    | 99.7       | 711.2  | 0.144       | 0.1773       | 0.239      | 0.1288          | 0.2977    | 0.07259            | B     |
| 20       | 13.08   | 15.71    | 85.63      | 520.0  | 0.1075      | 0.127        | 0.04568    | 0.0311          | 0.1967    | 0.06811            | 0.1852  | 0.7477   | 1.383      | 14.67 | 0.004097    | 0.01898      | 0.01698    | 0.00649         | 0.01678   | 0.002425           | 14.5    | 20.49    | 96.09      | 630.5  | 0.1312      | 0.2776       | 0.189      | 0.07283         | 0.3184    | 0.08183            | B     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic) for more information.