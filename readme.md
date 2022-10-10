# Center for Health Journalism: Data Fellowship 2022

------------------------------------------------------------------------

Liz Lucas [liz\@ire.org](mailto:liz@ire.org){.email}
Andrew Ba Tran [andrew.tran\@washpost.com]{.email}

## Getting Started

Learning to code with a language like R takes some time and effort on your part. We'll be covering a lot of foundation material this week, and sometimes this can feel like a firehouse of obscure information (e.g. what is an atomic vector and how is that different from a list) that you don't know what to do with yet. If you feel that way, that's OK! You will most likely have to go back and look this stuff up again. But it will help you get started today as we start flexing those coding muscles.

You should expect to feel some frustration, because everybody does. Frustration is OK so long as you can persevere through it. When you finally solve the problem and your code works it's a GREAT feeling.

## Get the files

## Before we move on, run these lines in console

```
install.packages(c("usethis", "tidyverse", "remotes"))

remotes::install_github("r-journalism/chjr", upgrade="always", quiet=TRUE)

usethis::use_course("https://github.com/r-journalism/chjr/archive/master.zip")
```


#### Resources
-   [Slideshow of R Basics](https://r-journalism.github.io/chjr/01_intro_to_r_rstudio.html#/title-slide)
-   [Slideshow of Wrangling Data](https://r-journalism.github.io/chjr/02_wrangling_data.html#/title-slide)
-   [Tidyverse documentation](https://www.tidyverse.org/): We'll be referring back to this a lot. Get used to reading documentation; it's an important skill!
-   [data](data/): Some of the data we'll be using for this class is in the data folder of this repository
-   [practice scripts](practice/): There are exercises in the practice folder that you can work on your own time


#### Practice
-   To practice creating and working with vectors and doing simple variable assignment, use [R-Basics.Rmd](practice/R-Basics.Rmd)
-   To practice importing and the basics of data analysis (sorting, filtering, aggregating), use [Importing-and-intro-to-data-analysis.Rmd](practice/Importing-and-intro-to-data-analysis.Rmd)

#### Day 1: Intro to R and RStudio
- [Slides]((https://r-journalism.github.io/chjr/01_intro_to_r_rstudio.html)
- `learnr::run_tutorial("1_intro_a", "chjr")`
- `learnr::run_tutorial("1_intro_b", "chjr")`
- `learnr::run_tutorial("1_intro_c", "chjr")`

#### Day 2: Wrangling data
- [Slides]((https://r-journalism.github.io/chjr/02_wrangling_data.html)
- `learnr::run_tutorial("2_a_exploring", "chjr")`
- `learnr::run_tutorial("2_b_filter_select", "chjr")`
- `learnr::run_tutorial("2_c_mutate_summarize", "chjr")`

#### Day 3: Transforming data


#### Day 4: Visualizing data



