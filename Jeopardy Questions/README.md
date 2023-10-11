# Jeopardy Questions Dataset
Jeopardy is a quiz show that has a unique answer-and-question format in which contestants are presented with clues in the form of answers and must phrase their responses in the form of a question.  
Questions [between year 1984 upto 2012] were obtained by crawling [www.j-archive.com](https://www.j-archive.com)

Creators:
  - [Unknown](https://unknown.org)

# More Details
| Associated Tasks                  | # Instances | # Features | Features Type | Class Type  | Missing Values |
| --------------------------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| natural language processing (NLP) | 216930      | 2          | Text          | Text        | true `3637`    |

Missing Values are considered as `null` in the dataset.

| # | Attribute Name | Role      | Type        | Units | Missing Values | Description                                                                                                         |
| - | -------------- | --------- | ----------- | ----- | -------------- | ------------------------------------------------------------------------------------------------------------------- |
| 0 | show-number    | meta-info | Numerical   |       | false          |                                                                                                                     |
| 1 | air-date       | meta-info | Temporal    |       | false          |                                                                                                                     |
| 2 | round          | meta-info | Categorical |       | false          | Tiebreaker questions do happen but they're very rare (like once every 20 years) which can be considered as outliers |
| 3 | category       | Feature   | Text        |       | false          |                                                                                                                     |
| 4 | value          | meta-info | Numerical   |       | true `3634`    | This is `null` for Final Jeopardy! and Tiebreaker questions                                                         |
| 5 | question       | Feature   | Text        |       | false          | This sometimes contains hyperlinks and other things messy text such as when there's a picture or video question     |
| 6 | answer         | `Target`  | Text        |       | true  `3`      |                                                                                                                     |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name                                          |
| - | -------------- | ------------ | -------------------------------------------------------- |
| 2 | round          | 4            | Jeopardy!, Double Jeopardy!, Final Jeopardy!, Tiebreaker |
```

## Some Samples
```
| # Sample | show-number | air-date   | round     | category                        | value | question                                                                                                    | answer     |
| -------- | ----------- | ---------- | --------- | ------------------------------- | ----- | ----------------------------------------------------------------------------------------------------------- | ---------- |
| 0        | 4680        | 2004-12-31 | Jeopardy! | HISTORY                         | $200  | For the last 8 years of his life, Galileo was under house arrest for espousing this man's theory            | Copernicus |
| 1        | 4680        | 2004-12-31 | Jeopardy! | ESPN's TOP 10 ALL-TIME ATHLETES | $200  | No. 2: 1912 Olympian; football star at Carlisle Indian School; 6 MLB seasons with the Reds, Giants & Braves | Jim Thorpe |
| 2        | 4680        | 2004-12-31 | Jeopardy! | EVERYBODY TALKS ABOUT IT...     | $200  | The city of Yuma in this state has a record average of 4,055 hours of sunshine each year                    | Arizona    |
| 3        | 4680        | 2004-12-31 | Jeopardy! | THE COMPANY LINE                | $200  | In 1963, live on "The Art Linkletter Show", this company served its billionth burger                        | McDonald's |
| 4        | 4680        | 2004-12-31 | Jeopardy! | EPITAPHS & TRIBUTES             | $200  | Signer of the Dec. of Indep., framer of the Constitution of Mass., second President of the United States    | John Adams |
| 5        | 4680        | 2004-12-31 | Jeopardy! | 3-LETTER WORDS                  | $200  | In the title of an Aesop fable, this insect shared billing with a grasshopper                               | the ant    |
```

# License
It seems like there is no specific license statement or agreement attached to the dataset by its creators or maintainers.

# Credit
Visit [reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/?rdt=47011](https://www.reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/?rdt=47011) for more information.