# SOC 312 Final Paper

## About

Final paper for Sociology 312: Women, criminality, and punishment. This paper focuses on the intersection of world values and prison systems.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START -->
| Contributions | Name (alpha order) |
| ----: | :---- |
| [🖋](# "Content") [💻](# "Code") [🤔](# "Ideas and Planning") [🔬](# "Research")| [Esa Schenck](https://github.com/esaschenck) |

<!-- ALL-CONTRIBUTORS-LIST:END -->

(For a key to the contribution emoji or more info on this format, check out [“All Contributors.”](https://allcontributors.org/docs/en/emoji-key))

## Dependencies

This project requires the following packages:

```{r}
library(tidyverse)
```


## Definitions

What are the key terms that guide your data analysis? For instance, if your group is studying "political partisanship" how have you defined that in your data work?

## Data Sources

All citations are included in the paper.

### World Values Survey

Data on international values is sourced from the [World Values Survey Wave 7 (2017-2022)](https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp), accessed March 26, 2023. Note that raw data is not provided for the World Values Survey, in accordance with their conditions of use.

Most raw data will be read with the following:

```{r}
dataframe <- read_csv("raw-data/data.csv")
```

However, the World Values Survey raw data will be read in this way:

```{r}
dataframe <- read_csv("../data.csv")
```

The `..` points to the *parent* directory of the repository. In order to reproduce this particular code, please download the WVS Wave 7 [here](https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp) and save to your forked repository's parent directory.


## Repo Architecture

How are files organized in the repository? Where should someone start? Where will they find the data sources - both original and cleaned?


## License

This repository is currently not covered under any license.


## How to Provide Feedback

Questions, bug reports, and feature requests can be submitted to this repo's [issue queue](https://github.com/esaschenck/soc-criminality-paper/issues).

