# Sentiment140 Dataset
It contains 1,600,000 tweets extracted using the twitter api in 2009.  
The tweets have been annotated (0 = negative, 1 = positive).  
Download dataset : [link](https://drive.google.com/drive/folders/10zZbpycHsJyH8PWhzUZj-zK01ha1gwKw)

Creators:
  - [Alec Go](https://www.linkedin.com/in/alecmgo)
  - [Richa Bhayani](https://www.linkedin.com/in/richabhayani)
  - [Lei Huang](https://www.linkedin.com/in/lei-huang-3b08ab11)

Note: There are some characters in this dataset like `♪♫` that are not supported in utf-8. load and save dataset as `encoding = "latin1"` [[ISO-8859-1](https://en.wikipedia.org/wiki/ISO/IEC_8859-1)].

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 1,600,000   | 1          | Text          | Categorical | false          |

| # | Attribute Name | Role      | Type        | Units | Missing Values | Description           |
| - | -------------- | --------- | ----------- | ----- | -------------- | --------------------- |
| 0 | user           | meta-info | Categorical |       | false          | the user that tweeted |
| 1 | id             | meta-info | Categorical |       | false          | the id of the tweet   |
| 2 | date           | meta-info | Temporal    |       | false          | the date of the tweet |
| 3 | text           | Feature   | Text        |       | false          | the text of the tweet |
| 4 | class          | `Target`  | Categorical |       | false          | sentiment type        |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name          |
| - | -------------- | ------------ | ------------------------ |
| 4 | class          | 2            | 0(Negative), 1(Positive) |
```

## Some Samples
```
| # Sample | user            | id         | data                         | text                                                                                           | class |
| -------- | --------------- | ---------- | ---------------------------- | ---------------------------------------------------------------------------------------------- | ----- |
|12        | TLeC            | 1467812723 | Mon Apr 06 22:20:19 PDT 2009 | @caregiving I couldn't bear to watch it.  And I thought the UA loss was embarrassing . . . . . | 0     |
|13        | robrobbierobert | 1467812771 | Mon Apr 06 22:20:19 PDT 2009 | @octolinz16 It it counts\, idk why I did either. you never talk to me anymore                  | 0     |
|1072839   | Neato_Burrito   | 1966653534 | Fri May 29 18:09:20 PDT 2009 | @rebeltex you're welcome! hope you're doing well                                               | 1     |
|1072886   | KYLESAYS        | 1966655898 | Fri May 29 18:09:35 PDT 2009 | @Angelus01 Thanks for the follow friday!                                                       | 1     |

```

# License
It seems like there is no specific license statement or agreement attached to the dataset by its creators or maintainers.

# Credit
The official website of the `Sentiment140` dataset: [http://help.sentiment140.com/for-students](http://help.sentiment140.com/for-students).