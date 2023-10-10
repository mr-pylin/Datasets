# Adult Dataset
Predict whether income exceeds `$50K/yr` based on census data. Also known as `Census Income` dataset.

Creators:
  - [Barry Becker](http://barrybecker4.com/resume/resume.html)
  - [Ronny Kohavi](https://robotics.stanford.edu/~ronnyk)

# More Details
| Associated Tasks | # Instances | # Features | Features Type          | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ---------------------- | ----------- | -------------- |
| Classification   | 48842       | 14         | Categorical, Numerical | Categorical | true `6465`    |

Missing Values are considered as `null` in the dataset.

| #  | Attribute Name | Role     | Type         | Units | Missing Values | Description      |
| -- | -------------- | -------- | ------------ | ----- | -------------- | ---------------- |
|  0 | age            | Feature  | Numerical    |       | false          |                  |
|  1 | workclass      | Feature  | Categorical  |       | `true 2799`    |                  |
|  2 | fnlwgt         | Feature  | Numerical    |       | false          |                  |
|  3 | education      | Feature  | Categorical  |       | false          |                  |
|  4 | education-num  | Feature  | Numerical    |       | false          |                  |
|  5 | marital-status | Feature  | Categorical  |       | false          |                  |
|  6 | occupation     | Feature  | Categorical  |       | `true 2809`    |                  |
|  7 | relationship   | Feature  | Categorical  |       | false          |                  |
|  8 | race           | Feature  | Categorical  |       | false          |                  |
|  9 | sex            | Feature  | Categorical  |       | false          |                  |
| 10 | capital-gain   | Feature  | Numerical    |       | false          |                  |
| 11 | capital-loss   | Feature  | Numerical    |       | false          |                  |
| 12 | hours-per-week | Feature  | Numerical    |       | false          |                  |
| 13 | native-country | Feature  | Categorical  |       | `true 857`     |                  |
| 14 | class          | `Target` | Categorical  |       | false          | amount of income |

## Categorical Attributes
```
| #  | Attribute Name | # Categories | Categories Name                                                                                                                                                                                                                                                                                                                                                                                                                |
| -- | -------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1  | workclass      | 8            | Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked                                                                                                                                                                                                                                                                                                                          |
| 3  | education      | 16           | Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool                                                                                                                                                                                                                                                                          |
| 5  | marital-status | 7            | Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse                                                                                                                                                                                                                                                                                                                      |
| 6  | occupation     | 14           | Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces                                                                                                                                                                                                       |
| 7  | relationship   | 6            | Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried                                                                                                                                                                                                                                                                                                                                                             |
| 8  | race           | 5            | White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black                                                                                                                                                                                                                                                                                                                                                                    |
| 9  | sex            | 2            | Female, Male                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 13 | native-country | 41           | United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands |
| 14 | class          | 2            | >50K, <=50K                                                                                                                                                                                                                                                                                                                                                                                                                    |
```

## Some Samples
```
| # Sample | age | workclass        | fnlwgt | education | education-num | marital-status        | occupation        | relationship  | race  | sex    | capital-gain | capital-loss | hours-per-week | native-country | class |
| -------- | --- | ---------------- | ------ | --------- | ------------- | --------------------- | ----------------- | ------------- | ----- | ------ | ------------ | ------------ | -------------- | -------------- | ----- |
| 0        | 39  | State-gov        | 77516  | Bachelors | 13            | Never-married         | Adm-clerical      | Not-in-family | White | Male   | 2174         | 0            | 40             | United-States  | <=50K |
| 1        | 50  | Self-emp-not-inc | 83311  | Bachelors | 13            | Married-civ-spouse    | Exec-managerial   | Husband       | White | Male   | 0            | 0            | 13             | United-States  | <=50K |
| 2        | 38  | Private          | 215646 | HS-grad   | 9             | Divorced              | Handlers-cleaners | Not-in-family | White | Male   | 0            | 0            | 40             | United-States  | <=50K |
| 3        | 53  | Private          | 234721 | 11th      | 7             | Married-civ-spouse    | Handlers-cleaners | Husband       | Black | Male   | 0            | 0            | 40             | United-States  | <=50K |
| 4        | 28  | Private          | 338409 | Bachelors | 13            | Married-civ-spouse    | Prof-specialty    | Wife          | Black | Female | 0            | 0            | 40             | Cuba           | <=50K |
| 5        | 37  | Private          | 284582 | Masters   | 14            | Married-civ-spouse    | Exec-managerial   | Wife          | White | Female | 0            | 0            | 40             | United-States  | <=50K |
| 6        | 49  | Private          | 160187 | 9th       | 5             | Married-spouse-absent | Other-service     | Not-in-family | Black | Female | 0            | 0            | 16             | Jamaica        | <=50K |
| 7        | 52  | Self-emp-not-inc | 209642 | HS-grad   | 9             | Married-civ-spouse    | Exec-managerial   | Husband       | White | Male   | 0            | 0            | 45             | United-States  | >50K  |
| 8        | 31  | Private          | 45781  | Masters   | 14            | Never-married         | Prof-specialty    | Not-in-family | White | Female | 14084        | 0            | 50             | United-States  | >50K  |
| 9        | 42  | Private          | 159449 | Bachelors | 13            | Married-civ-spouse    | Exec-managerial   | Husband       | White | Male   | 5178         | 0            | 40             | United-States  | >50K  |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/2/adult](https://archive.ics.uci.edu/dataset/2/adult) for more information.