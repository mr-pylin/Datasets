# Zoo Dataset
A simple database containing 17 Boolean-valued attributes to classify animals in similar groups.

Creators:
  - [Richard Forsyth](https://www.richardsandesforsyth.net)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 101         | 17         | Categorical   | Categorical | false          |

| #  | Attribute Name | Role     | Type        | Units | Missing Values | Description |
| -- | -------------- | -------- | ----------- | ----- | -------------- | ----------- |
| 0  | animal-name    | Feature  | Categorical |       | false          |             |
| 1  | hair           | Feature  | Categorical |       | false          |             |
| 2  | feathers       | Feature  | Categorical |       | false          |             |
| 3  | eggs           | Feature  | Categorical |       | false          |             |
| 4  | milk           | Feature  | Categorical |       | false          |             |
| 5  | airborne       | Feature  | Categorical |       | false          |             |
| 6  | aquatic        | Feature  | Categorical |       | false          |             |
| 7  | predator       | Feature  | Categorical |       | false          |             |
| 8  | toothed        | Feature  | Categorical |       | false          |             |
| 9  | backbone       | Feature  | Categorical |       | false          |             |
| 10 | breathes       | Feature  | Categorical |       | false          |             |
| 11 | venomous       | Feature  | Categorical |       | false          |             |
| 12 | fins           | Feature  | Categorical |       | false          |             |
| 13 | legs           | Feature  | Categorical |       | false          |             |
| 14 | tail           | Feature  | Categorical |       | false          |             |
| 15 | domestic       | Feature  | Categorical |       | false          |             |
| 16 | catsize        | Feature  | Categorical |       | false          |             |
| 17 | class          | `Target` | Categorical |       | false          | animal type |

## Categorical Attributes
```
| #  | Attribute Name | # Categories | Categories Name                                           |
| -- | -------------- | ------------ | --------------------------------------------------------- |
| 17 | class          | 7            | mammal, bird, reptile, fish, amphibian, bug, invertebrate |

mammal       : aardvark, antelope, bear, boar, buffalo, calf, cavy, cheetah, deer, dolphin, elephant, fruitbat, giraffe, girl, goat, gorilla, hamster, hare, leopard, lion, lynx, mink, mole, mongoose, opossum, oryx, platypus, polecat, pony, porpoise, puma, pussycat, raccoon, reindeer, seal, sealion, squirrel, vampire, vole, wallaby, wolf
bird         : chicken, crow, dove, duck, flamingo, gull, hawk, kiwi, lark, ostrich, parakeet, penguin, pheasant, rhea, skimmer, skua, sparrow, swan, vulture, wren
reptile      : pitviper, seasnake, slowworm, tortoise, tuatara
fish         : bass, carp, catfish, chub, dogfish, haddock, herring, pike, piranha, seahorse, sole, stingray, tuna
amphibian    : frog, frog, newt, toad
bug          : flea, gnat, honeybee, housefly, ladybird, moth, termite, wasp
invertebrate : clam, crab, crayfish, lobster, octopus, scorpion, seawasp, slug, starfish, worm
```

## Some Samples
Samples are chosen from white-wine dataset
```
| # Sample | animal-name | hair | feathers | eggs | milk | airborne | aquatic | predator | toothed | backbone | breathes | venomous | fins | legs | tail | domestic | catsize | class |
| -------- | ----------- | ---- | -------- | ---- | ---- | -------- | ------- | -------- | ------- | -------- | -------- | -------- | ---- | ---- | ---- | -------- | ------- | ----- |
| 0        | aardvark    | 1    | 0        | 0    | 1    | 0        | 0       | 1        | 1       | 1        | 1        | 0        | 0    | 4    | 0    | 0        | 1       | 1     |
| 11       | chicken     | 0    | 1        | 1    | 0    | 1        | 0       | 0        | 0       | 1        | 1        | 0        | 0    | 2    | 1    | 1        | 0       | 2     |
| 62       | pitviper    | 0    | 0        | 1    | 0    | 0        | 0       | 1        | 1       | 1        | 1        | 1        | 0    | 0    | 1    | 0        | 0       | 3     |
| 73       | seahorse    | 0    | 0        | 1    | 0    | 0        | 1       | 0        | 1       | 1        | 0        | 0        | 1    | 0    | 1    | 0        | 0       | 4     |
| 89       | toad        | 0    | 0        | 1    | 0    | 0        | 1       | 0        | 1       | 1        | 1        | 0        | 0    | 4    | 0    | 0        | 0       | 5     |
| 97       | wasp        | 1    | 0        | 1    | 0    | 1        | 0       | 0        | 0       | 0        | 1        | 1        | 0    | 6    | 0    | 0        | 0       | 6     |
| 99       | worm        | 0    | 0        | 1    | 0    | 0        | 0       | 0        | 0       | 0        | 1        | 0        | 0    | 0    | 0    | 0        | 0       | 7     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/111/zoo](https://archive.ics.uci.edu/dataset/111/zoo) for more information.