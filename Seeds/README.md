# Seeds Dataset
Measurements of geometrical properties of kernels belonging to three different varieties of wheat.  
A soft X-ray technique and GRAINS package were used to construct all seven, real-valued attributes.

Creators:
  - [Magorzata Charytanowicz](https://scholar.google.pl/citations?user=MfsOr4cAAAAJ&hl)
  - [Jerzy Niewczas](https://scholar.google.com/citations?user=9mEQY8sAAAAJ&hl)
  - [Piotr Kulczycki](https://scholar.google.pl/citations?user=UcaDXE4AAAAJ&hl)
  - [Piotr Kowalski](https://scholar.google.com/citations?user=AXjLN0YAAAAJ&hl)
  - [Szymon Lukasik](https://scholar.google.com/citations?user=-O9fFQwAAAAJ&hl)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 210         | 7          | Numerical     | Categorical | false          |

| # | Attribute Name | Role     | Type        | Units | Missing Values | Description                        |
| - | -------------- | -------- | ----------- | ----- | -------------- | ---------------------------------- |
| 0 | a              | Feature  | Numerical   |       | false          | area                               |
| 1 | p              | Feature  | Numerical   |       | false          | perimeter                          |
| 2 | c              | Feature  | Numerical   |       | false          | compactness [(4 * pi * A) / P ^ 2] |
| 3 | lok            | Feature  | Numerical   |       | false          | length of kernel                   |
| 4 | wok            | Feature  | Numerical   |       | false          | width of kernel                    |
| 5 | ac             | Feature  | Numerical   |       | false          | asymmetry coefficient              |
| 6 | lokg           | Feature  | Numerical   |       | false          | length of kernel groove            |
| 7 | class          | `Target` | Categorical |       | false          | wheat type                         |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name               |
| - | -------------- | ------------ | ----------------------------- |
| 7 | class          | 3            | 1(Kama), 2(Rosa), 3(Canadian) |
```

## Some Samples
```
| # Sample | a     | p     | c      | lok   | wok   | ac    | lokg  | class |
| -------- | ----- | ----- | ------ | ----- | ----- | ----- | ----- | ----- |
| 0        | 15.26 | 14.84 | 0.871  | 5.763 | 3.312 | 2.221 | 5.22  | 1     |
| 1        | 14.88 | 14.57 | 0.8811 | 5.554 | 3.333 | 1.018 | 4.956 | 1     |
| 70       | 17.63 | 15.98 | 0.8673 | 6.191 | 3.561 | 4.076 | 6.06  | 2     |
| 71       | 16.84 | 15.67 | 0.8623 | 5.998 | 3.484 | 4.675 | 5.877 | 2     |
| 140      | 13.07 | 13.92 | 0.848  | 5.472 | 2.994 | 5.304 | 5.395 | 3     |
| 141      | 13.32 | 13.94 | 0.8613 | 5.541 | 3.073 | 7.035 | 5.44  | 3     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/236/seeds](https://archive.ics.uci.edu/dataset/236/seeds) for more information.