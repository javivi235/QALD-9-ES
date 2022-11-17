# QALD-9-ES Dataset Description

QALD-9-ES is the dataset for Knowledge Graph Question Answering (KGQA) based on [QALD-9-plus](https://github.com/KGQA/QALD_9_plus) wich is based on [QALD-9](https://github.com/ag-sc/QALD/tree/master/9/data) dataset.

QALD-9-ES adds to the original 9 languages of QALD-9-plus Spanish translations making it available in 10 different languages: English, German, Russian, French, Armenian, Belarusian, Lithuanian, Bashkir, Ukrainian, and Spanish.

As the questions' translations were provided by native speakers, they are considered as "gold standard", therefore, machine translation tools can be trained and evaluated on the dataset.

# Dataset Statistics

|       |  en |  de | fr |  ru  |  uk |  lt |  be |  ba | hy | es | # questions DBpedia | # questions Wikidata |
|-------|:---:|:---:|:--:|:----:|:---:|:---:|:---:|:---:|:--:|:--:|:-----------:|:-----------:|
| Train | 408 | 543 | 260 | 1203 | 447 | 468 | 441 | 284 | 80 | 408 |     408     |     371     |
| Test  | 150 | 176 | 26 |  348 | 176 | 186 | 155 | 117 | 20 | 150 |    150     |     136     |

As you can appreciate some languages are covered more than once i.e., Russion has 1203 translations available when there are only 408 unique questions having 2.9 translations per question, this is thanks to the efforts of the QALD-9-plus team.


# Evaluation

We used [GERBIL](https://github.com/dice-group/gerbil/) system for the evaluation of the dataset. The detailed information for the experiments is available at the individual link (click the value in the cells).

## Wikidata

### QAnswer

# Licence [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

