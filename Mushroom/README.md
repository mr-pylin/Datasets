# Mushroom Dataset
Mushrooms are described in terms of physical characteristics to be classified as `poisonous` or `edible`.

Creators:
  - [Unknown](https://unknown.org)

# More Details
| Associated Tasks | # Instances | # Features | Features Type | Class Type  | Missing Values |
| ---------------- | ----------- | ---------- | ------------- | ----------- | -------------- |
| Classification   | 8124        | 22         | Categorical   | Categorical | true `2480`    |

Missing Values are considered as `null` in the dataset.

| #  | Attribute Name           | Role     | Type        | Units | Missing Values | Description   |
| -- | ------------------------ | -------- | ----------- | ----- | -------------- | ------------- |
|  0 | cap-shape                | Feature  | Categorical |       | false          |               |
|  1 | cap-surface              | Feature  | Categorical |       | false          |               |
|  2 | cap-color                | Feature  | Categorical |       | false          |               |
|  3 | bruises?                 | Feature  | Categorical |       | false          |               |
|  4 | odor                     | Feature  | Categorical |       | false          |               |
|  5 | gill-attachment          | Feature  | Categorical |       | false          |               |
|  6 | gill-spacing             | Feature  | Categorical |       | false          |               |
|  7 | gill-size                | Feature  | Categorical |       | false          |               |
|  8 | gill-color               | Feature  | Categorical |       | false          |               |
|  9 | stalk-shape              | Feature  | Categorical |       | false          |               |
| 10 | stalk-root               | Feature  | Categorical |       | `true 2480`    |               |
| 11 | stalk-surface-above-ring | Feature  | Categorical |       | false          |               |
| 12 | stalk-surface-below-ring | Feature  | Categorical |       | false          |               |
| 13 | stalk-color-above-ring   | Feature  | Categorical |       | false          |               |
| 14 | stalk-color-below-ring   | Feature  | Categorical |       | false          |               |
| 15 | veil-type                | Feature  | Categorical |       | false          |               |
| 16 | veil-color               | Feature  | Categorical |       | false          |               |
| 17 | ring-number              | Feature  | Categorical |       | false          |               |
| 18 | ring-type                | Feature  | Categorical |       | false          |               |
| 19 | spore-print-color        | Feature  | Categorical |       | false          |               |
| 20 | population               | Feature  | Categorical |       | false          |               |
| 21 | habitat                  | Feature  | Categorical |       | false          |               |
| 22 | class                    | `Target` | Categorical |       | false          | mushroom type |

## Categorical Attributes
`Note:` "Unavailable Categories", mean that there are no instances in this dataset assigned to that category [but that categories are mentioned in the original reference].
```
| #  | Attribute Name            | # Categories | Available Categories                                                                                                     | Unavailable Categories             |                                                                                                         |
| -- | ------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------ | ---------------------------------- |
| 0  | cap-shape                 | 6            | bell(b), conical(c), convex(x), flat(f), knobbed(k), sunken(s)                                                           |                                    |
| 1  | cap-surface               | 4            | fibrous(f), grooves(g), scaly(y), smooth(s)                                                                              |                                    |
| 2  | cap-color                 | 10           | brown(n), buff(b), cinnamon(c), gray(g), green(r), pink(p), purple(u), red(e), white(w), yellow(y)                       |                                    |
| 3  | bruises?                  | 2            | has-bruises(t), no(f)                                                                                                    |                                    |
| 4  | odor                      | 9            | almond(a), anise(l), creosote(c), fishy(y), foul(f), musty(m), none(n), pungent(p), spicy(s)                             |                                    |
| 5  | gill-attachment           | 4            | attached(a), free(f)                                                                                                     | descending(d), notched(n)          |                                                                    |
| 6  | gill-spacing              | 3            | close(c), crowded(w)                                                                                                     | distant(d)                         |                                                                    |
| 7  | gill-size                 | 2            | broad(b), narrow(n)                                                                                                      |                                    |
| 8  | gill-color                | 12           | black(k), brown(n), buff(b), chocolate(h), gray(g), green(r), orange(o), pink(p), purple(u), red(e), white(w), yellow(y) |                                    |
| 9  | stalk-shape               | 2            | enlarging(e), tapering(t)                                                                                                |                                    |
| 10 | stalk-root                | 6            | bulbous(b), rooted(r), cup(u), equal(e)                                                                                  | rhizomorphs(z), club(c)            | 
| 11 | stalk-surface-above-ring  | 4            | fibrous(f), smooth(s), scaly(y), silky(k)                                                                                |                                    |
| 12 | stalk-surface-below-ring  | 4            | fibrous(f), smooth(s), scaly(y), silky(k)                                                                                |                                    |
| 13 | stalk-color-above-ring    | 9            | buff(b), brown(n), cinnamon(c), gray(g), orange(o), pink(p), red(e), white(w), yellow(y)                                 |                                    |
| 14 | stalk-color-below-ring    | 9            | buff(b), brown(n), cinnamon(c), gray(g), orange(o), pink(p), red(e), white(w), yellow(y)                                 |                                    |
| 15 | veil-type                 | 2            | partial(p)                                                                                                               | universal(u)                       |
| 16 | veil-color                | 4            | brown(n), orange(o), white(w), yellow(y)                                                                                 |                                    |
| 17 | ring-number               | 3            | none(n), one(o), two(t)                                                                                                  |                                    |
| 18 | ring-type                 | 8            | evanescent(e), flaring(f), large(l), none(n), pendant(p)                                                                 | sheathing(s), zone(z), cobwebby(c) |
| 19 | spore-print-color         | 9            | black(k), brown(n), buff(b), chocolate(h), green(r), orange(o), purple(u), white(w), yellow(y)                           |                                    |
| 20 | population                | 6            | abundant(a), clustered(c), numerous(n),  scattered(s), several(v), solitary(y)                                           |                                    |
| 21 | habitat                   | 7            | grasses(g), leaves(l), meadows(m), paths(p), urban(u), waste(w), woods(d)                                                |                                    |
| 22 | class                     | 3            | edible(e), poisonous(p)                                                                                                  | unknown(u)                         |
```

## Some Samples
```
| # Sample | cap-shape | cap-surface | cap-color | bruises? | odor | gill-attachment | gill-spacing | gill-size | gill-color | stalk-shape | stalk-root | stalk-surface-above-ring | stalk-surface-below-ring | stalk-color-above-ring | stalk-color-below-ring | veil-type | veil-color | ring-number | ring-type | spore-print-color | population | habitat | class |
| -------- | --------- | ----------- | --------- | -------- | ---- | --------------- | ------------ | --------- | ---------- | ----------- | ---------- | ------------------------ | ------------------------ | ---------------------- | ---------------------- | --------- | ---------- | ----------- | --------- | ----------------- | ---------- | ------- | ----- |
| 0        | x         | s           | n         | t        | p    | f               | c            | n         | k          | e           | e          | s                        | s                        | w                      | w                      | p         | w          | o           | p         | k                 | s          | u       | p     |
| 1        | x         | s           | y         | t        | a    | f               | c            | b         | k          | e           | c          | s                        | s                        | w                      | w                      | p         | w          | o           | p         | n                 | n          | g       | e     |
| 2        | b         | s           | w         | t        | l    | f               | c            | b         | n          | e           | c          | s                        | s                        | w                      | w                      | p         | w          | o           | p         | n                 | n          | m       | e     |
| 3        | x         | y           | w         | t        | p    | f               | c            | n         | n          | e           | e          | s                        | s                        | w                      | w                      | p         | w          | o           | p         | k                 | s          | u       | p     |
| 4        | x         | s           | g         | f        | n    | f               | w            | b         | k          | t           | e          | s                        | s                        | w                      | w                      | p         | w          | o           | e         | n                 | a          | g       | e     |
```

# License
This dataset is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) (`CC BY 4.0`) license.  
TL;DR: This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.

# Credit
Visit [archive.ics.uci.edu/dataset/73/mushroom](https://archive.ics.uci.edu/dataset/73/mushroom) for more information.