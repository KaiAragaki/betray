
<!-- README.md is generated from README.Rmd. Please edit that file -->

# betray

<!-- badges: start -->
<!-- badges: end -->

## Installation

You can install the development version of betray from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("KaiAragaki/betray")
```

## About

This package contains character data from [Betrayal at House on the
Hill](https://en.wikipedia.org/wiki/Betrayal_at_House_on_the_Hill) (2nd
Edition, 2021, Hasbro)

``` r
library(betray)
library(dplyr)
betray |> 
  select(hero:speed_init_pos) |> 
  kable()
```

| hero                    | color   | age | height | weight | hobbies                                  | birthday   | speed                     | speed_init_pos |
|:------------------------|:--------|----:|-------:|-------:|:-----------------------------------------|:-----------|:--------------------------|---------------:|
| Zoe Ingstrom            | #cd6b41 |   8 |     45 |     49 | Dolls, Music                             | 1995-11-05 | 0, 4, 4, 4, 4, 5, 6, 8, 8 |              5 |
| Missy Dubourde          | #cd6b41 |   9 |     50 |     62 | Swimming, Medicine                       | 1994-02-14 | 0, 3, 4, 5, 6, 6, 6, 7, 7 |              4 |
| Father Rhinehardt       | #ffffff |  62 |     69 |    185 | Fencing , Gardening                      | 1941-04-29 | 0, 2, 3, 3, 4, 5, 6, 7, 7 |              4 |
| Professor Longfellow    | #ffffff |  57 |     71 |    153 | Gaelic Music, Drama , Fine Wines         | 1946-07-27 | 0, 2, 2, 4, 4, 5, 5, 6, 6 |              5 |
| Jenny LeClerc           | #8f2d80 |  21 |     67 |    142 | Reading, Soccer                          | 1982-03-04 | 0, 2, 3, 4, 4, 4, 5, 6, 8 |              5 |
| Heather Granville       | #8f2d80 |  18 |     62 |    120 | Television, Shopping                     | 1985-08-02 | 0, 3, 3, 4, 5, 6, 6, 7, 8 |              4 |
| Ox Bellows              | #a4121f |  23 |     76 |    288 | Football , Shiny Objects                 | 1980-10-18 | 0, 2, 2, 2, 3, 4, 5, 5, 6 |              6 |
| Darrin “Flash” Williams | #a4121f |  20 |     71 |    188 | Track , Music , Shakespearean Literature | 1983-06-06 | 0, 4, 4, 4, 5, 6, 7, 7, 8 |              6 |
| Madame Zostra           | #206fb5 |  37 |     60 |    150 | Astrology, Cooking , Baseball            | 1966-12-10 | 0, 2, 3, 3, 5, 5, 6, 6, 7 |              4 |
| Vivian Lopez            | #206fb5 |  42 |     65 |    142 | Old Movies, Horses                       | 1961-01-11 | 0, 3, 4, 4, 4, 4, 6, 7, 8 |              5 |
| Brandon Jaspers         | #2dc164 |  12 |     61 |    109 | Computers, Camping , Hockey              | 1991-05-21 | 0, 3, 4, 4, 4, 5, 6, 7, 8 |              4 |
| Peter Akimoto           | #2dc164 |  13 |     59 |     98 | Bugs , Basketball                        | 1990-09-03 | 0, 3, 3, 3, 4, 6, 6, 7, 7 |              5 |
