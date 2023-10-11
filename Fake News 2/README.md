# Fake News 2 Dataset
This dataset was used for a competition in the [Kaggle](https://www.kaggle.com).  
The evaluation metric for this competition is `accuracy`.  
Note: `class` column is missing for testset because it was a competition.  
Download dataset : [link](https://drive.google.com/drive/folders/1s380ic2UaO4RdqPbMOQFHNr32ZV8JL1X)

Creators:
  - [William Lifferth](https://www.linkedin.com/in/wlifferth)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 26000       | 2          | Text          | Categorical | true `3186`    |

Missing Values are considered as `null` in the dataset.

| # | Attribute Name | Role      | Type        | Units | Missing Values | Description |
| - | -------------- | --------- | ----------- | ----- | -------------- | ----------- |
| 0 | id             | meta-info | Index       |       | false          |             |
| 1 | title          | Feature   | Text        |       | true `680`     |             |
| 2 | author         | meta-info | Categorical |       | true `2460`    |             |
| 3 | text           | Feature   | Text        |       | true `46`      |             |
| 4 | label          | `Target`  | Categorical |       | false          |             |

## Categorical Attributes
```
| # | Attribute Name | # Categories | Categories Name            |
| - | -------------- | ------------ | -------------------------- |
| 4 | label          | 2            | 0(reliable), 1(unreliable) |
```

## Some Samples
Note: new spaces are shown as `\n` in the below samples.
```
| # Sample | id | title                                                                                                                        | author             | text                                                                                                                                                                                                                                                                                                           | label |
| -------- | -- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- |
| 0        | 0  | House Dem Aide: We Didn't Even See Comey's Letter Until Jason Chaffetz Tweeted It                                            | Darrell Lucus      | House Dem Aide: We Didn't Even See Comey's Letter Until Jason Chaffetz Tweeted It By Darrell Lucus on October 30, 2016 Subscribe Jason Chaffetz on the stump in American Fork, Utah ( image courtesy Michael Jolley, available under a Creative Commons-BY license) \nWith apologies to Keith Olbermann, ..... | 1     |
| 1        | 1  | FLYNN: Hillary Clinton, Big Woman on Campus - Breitbart                                                                      | Daniel J. Flynn    | Ever get the feeling your life circles the roundabout rather than heads in a straight line toward the intended destination? [Hillary Clinton remains the big woman on campus in leafy, liberal Wellesley, Massachusetts.                                                                                 ..... | 0     |
| 2        | 2  | Why the Truth Might Get You Fired                                                                                            | Consortiumnews.com | Why the Truth Might Get You Fired October 29, 2016 \nThe tension between intelligence analysts and political policymakers has always been between honest assessments and desired results, with the latter often overwhelming the former, as in the Iraq War, writes Lawrence Davidson.                   ..... | 1     |
| 3        | 3  | 15 Civilians Killed In Single US Airstrike Have Been Identified                                                              | Jessica Purkiss    | Videos 15 Civilians Killed In Single US Airstrike Have Been Identified The rate at which civilians are being killed by American airstrikes in Afghanistan is now higher than it was in 2014 when the US was engaged in active combat operations.                                                         ..... | 1     |
| 4        | 4  | Iranian woman jailed for fictional unpublished story about woman stoned to death for adultery                                | Howard Portnoy     | Print \nAn Iranian woman has been sentenced to six years in prison after Iran's Revolutionary Guard searched her home and found a notebook that contained a fictional story she'd written about a woman who was stoned to death, according to the Eurasia Review . \nGolrokh Ebrahimi Iraee,             ..... | 1     |
| 5        | 5  | Jackie Mason: Hollywood Would Love Trump if He Bombed North Korea over Lack of Trans Bathrooms (Exclusive Video) - Breitbart | Daniel Nussbaum    | In these trying times, Jackie Mason is the Voice of Reason. [In this week's exclusive clip for Breitbart News, Jackie discusses the looming threat of North Korea, and explains how President Donald Trump could win the support of the Hollywood left if the U. S. needs to strike first.               ..... | 0     |
```

# License
It seems like there is no specific license statement or agreement attached to the dataset by its creators or maintainers.

# Credit
Visit [www.kaggle.com/competitions/fake-news](https://www.kaggle.com/competitions/fake-news) for more information.