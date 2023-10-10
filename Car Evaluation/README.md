# Car Evaluation Dataset
Cars in terms of some characteristics are evaluated to be `unacceptable`, `acceptable`, `good`, `very-good`.

Creators:
  - [Marko Bohanec](https://kt.ijs.si/MarkoBohanec/mare.html)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 1728        | 6          | Categorical   | Categorical | false          |

| # | Attribute Name | Role     | Type        | Units | Missing Values | Description                           |
| - | -------------- | -------- | ----------- | ----- | -------------- | ------------------------------------- |
| 0 | buying         | Feature  | Categorical |       | false          | buying price                          |
| 1 | maint          | Feature  | Categorical |       | false          | price of the maintenance              |
| 2 | doors          | Feature  | Categorical |       | false          | number of doors                       |
| 3 | persons        | Feature  | Categorical |       | false          | capacity in terms of persons to carry |
| 4 | lug-boot       | Feature  | Categorical |       | false          | the size of luggage boot              |
| 5 | safety         | Feature  | Categorical |       | false          | estimated safety of the car           |
| 6 | class          | `Target` | Categorical |       | false          | car value                             |

## Categorical Attributes
```
| #  | Attribute Name | # Categories | Categories Name         |
| -- | -------------- | ------------ | ----------------------- |
| 0  | buying         | 4            | vhigh, high, med, low   |
| 1  | maint          | 4            | vhigh, high, med, low   |
| 2  | doors          | 4            | 2, 3, 4, 5more          |
| 3  | persons        | 3            | 2, 4, more              |
| 4  | lug-boot       | 3            | small, med, big         |
| 5  | safety         | 3            | low, med, high          |
| 6  | class          | 4            | unacc, acc, vgood, good |
```

## Some Samples
```
| # Sample | buying | maint | doors | persons | lug-boot | safety | class |
| -------- | ------ | ----- | ----- | ------- | -------- | ------ | ----- |
| 0        | vhigh  | vhigh | 2     | 2       | small    | low    | unacc |
| 1        | vhigh  | vhigh | 2     | 2       | small    | med    | unacc |
| 310      | vhigh  | med   | 5more | 4       | med      | med    | acc   |
| 311      | vhigh  | med   | 5more | 4       | med      | high   | acc   |
| 1253     | med    | low   | 4     | 4       | small    | high   | good  |
| 1255     | med    | low   | 4     | 4       | med      | med    | good  |
| 1715     | low    | low   | 5more | 4       | med      | high   | vgood |
| 1718     | low    | low   | 5more | 4       | big      | high   | vgood |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/19/car+evaluation](https://archive.ics.uci.edu/dataset/19/car+evaluation) for more information.