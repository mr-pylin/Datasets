# Fake News Dataset
A decade-long of 12.8K manually labeled short statements were collected in various contexts from [politifact.com](https://politifact.com).  
There are `10,270` training news, `1,284` validation news and `1,284` test news.  
There are some empty values marked as `none` which shall not be considered as a missing value.

Creators:
  - [William Wang](https://sites.cs.ucsb.edu/~william)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 12838       | 1          | Text          | Categorical | true `6440`    |

Missing Values are considered as `null` in the dataset.

| #  | Attribute Name       | Role      | Type        | Units | Missing Values | Description |
| -- | -------------------- | --------- | ----------- | ----- | -------------- | ----------- |
| 0  | id                   | meta-info | Text        |       | false          |             |
| 1  | class                | `Target`  | Categorical |       | false          |             |
| 2  | statement            | Feature   | Text        |       | false          |             |
| 3  | subject              | meta-info | Text        |       | false          |             |
| 4  | speaker              | meta-info | Categorical |       | false          |             |
| 5  | job_title            | meta-info | Categorical |       | true `3564`    |             |
| 6  | state_info           | meta-info | Categorical |       | true `2747`    |             |
| 7  | party_affiliation    | meta-info | Numeric     |       | false          |             |
| 8  | barely_true_counts   | meta-info | Numeric     |       | false          |             |
| 9  | false_counts         | meta-info | Numeric     |       | false          |             |
| 10 | half_true_counts     | meta-info | Numeric     |       | false          |             |
| 11 | mostly_true_counts   | meta-info | Numeric     |       | false          |             |
| 12 | pants_on_fire_counts | meta-info | Numeric     |       | false          |             |
| 13 | context              | meta-info | Text        |       | true `129`     |             |


## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name                                               |
| - | -------------- | ------------ | ------------------------------------------------------------- |
| 1 | class          | 6            | false, half-true, mostly-true, true, barely-true, pants-fire  |
| 2 | speaker        | 3312         | dwayne-bohac, scott-surovell, barack-obama, ...               |
| 3 | job_title      | 1359         | State delegate, President, U.S. Senator, Former governor, ... |
| 4 | state_info     | 88           | Texas, Virginia, Illinois, Florida, Wisconsin, ...            |
```

## Some Samples
Samples are chosen from trainset.
```
| # Sample | id         | class       | statement                                                                                                                                                   | subject                            | speaker        | job_title                  | state_info | party_affiliation | barely_true_counts | false_counts | half_true_counts | mostly_true_counts | pants_on_fire_counts | context                   |
| -------- | ---------- | ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | -------------- | -------------------------- | ---------- | ----------------- | ------------------ | ------------ | ---------------- | ------------------ | -------------------- | ------------------------- |
| 0        | 2635.json  | false       | Says the Annies List political group supports third-trimester abortions on demand.                                                                          | abortion                           | dwayne-bohac   | State representative       | Texas      | republican        | 0                  | 1            | 0                | 0                  | 0                    | a mailer                  |
| 1        | 10540.json | half-true   | When did the decline of coal start? It started when natural gas took off that started to begin in (President George W.) Bushs administration.               | energy,history,job-accomplishments | scott-surovell | State delegate             | Virginia   | democrat          | 0                  | 0            | 1                | 1                  | 0                    | a floor speech.           |
| 2        | 324.json   | mostly-true | Hillary Clinton agrees with John McCain "by voting to give George Bush the benefit of the doubt on Iran.                                                    | foreign-policy                     | barack-obama   | President                  | Illinois   | democrat          | 70                 | 71           | 160              | 163                | 9                    | Denver                    |
| 3        | 1123.json  | false       | Health care reform legislation is likely to mandate free sex change surgeries.                                                                              | health-care                        | blog-posting   | null                       | null       | none              | 7                  | 19           | 3                | 5                  | 44                   | a news release            |
| 4        | 9028.json  | half-true   | The economic turnaround started at the end of my term.                                                                                                      | economy,jobs                       | charlie-crist  | null                       | Florida    | democrat          | 15                 | 9            | 20               | 19                 | 2                    | an interview on CNN       |
| 5        | 12465.json | true        | The Chicago Bears have had more starting quarterbacks in the last 10 years than the total number of tenured (UW) faculty fired during the last two decades. | education                          | robin-vos      | Wisconsin Assembly speaker | Wisconsin  | republican        | 0                  | 3            | 2                | 5                  | 1                    | a an online opinion-piece |
```

# License
It seems like there is no specific license statement or agreement attached to the dataset by its creators or maintainers.

# Credit
Visit [sites.cs.ucsb.edu/~william/data/liar_dataset.zip](https://sites.cs.ucsb.edu/~william/data/liar_dataset.zip) for more information.