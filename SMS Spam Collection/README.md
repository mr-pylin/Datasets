# SMSSpamCollection Dataset
The SMS Spam Collection is a public set of SMS labeled messages that have been collected for mobile phone spam research.

Creators:
  - [Tiago A. Almeida](https://scholar.google.com.br/citations?user=cZmF9fwAAAAJ&hl=en)
  - [Jose Maria Gomez Hidalgo](https://scholar.google.com/citations?user=LqUF1SkAAAAJ&hl=en)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 5574        | 1          | Text          | Categorical | false          |

| # | Attribute Name | Role     | Type        | Units | Missing Values | Description         |
| - | -------------- | -------- | ----------- | ----- | -------------- | ------------------- |
| 0 | class          | `Target` | Categorical |       | false          | spam or not         |
| 1 | text           | Feature  | Text        |       | false          | the text of the SMS |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name |
| - | -------------- | ------------ | --------------- |
| 0 | class          | 2            | ham, spam       |
```

## Some Samples
```
| # Sample | class | text                                                                                                                                      |
| -------- | ----- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| 1        | ham   | Ok lar... Joking wif u oni...                                                                                                             |
| 4        | ham   | Nah I don't think he goes to usf, he lives around here though                                                                             |
| 68       | spam  | Did you hear about the new "Divorce Barbie"? It comes with all of Ken's stuff!                                                            |
| 93       | spam  | Please call our customer service representative on 0800 169 6031 between 10am-9pm as you have WON a guaranteed £1000 cash or £5000 prize! |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/228/sms+spam+collection](https://archive.ics.uci.edu/dataset/228/sms+spam+collection) for more information.