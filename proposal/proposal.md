Project proposal
================
Team name

``` r
library(tidyverse)
library(broom)
```

## 1. Introduction

## 2. Data

``` r
library(readr)
X2011_us <- read_csv("../data/2011_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 82456 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (27): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (85): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (7): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
X2011_us <- X2011_us %>%
  select()
```

## 3. Ethics review

## 4. Data analysis plan
