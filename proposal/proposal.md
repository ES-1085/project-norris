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
tri_data_2011 <- read_csv("../data/2011_us.csv")
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
tri_data_2011 <- tri_data_2011 %>%
  select()

library(readr)
tri_data_2012 <- read_csv("../data/2012_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 82842 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (27): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (85): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (7): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2012 <-  tri_data_2012 %>% 
  select()

library(readr)
tri_data_2013 <- read_csv("../data/2013_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 83356 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (27): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (85): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (7): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2013 <- tri_data_2013 %>% 
  select()

library(readr)
tri_data_2014 <- read_csv("../data/2014_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 83590 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (85): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (6): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2014 <- tri_data_2014 %>% 
  select()

library(readr)
tri_data_2015 <- read_csv("../data/2015_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 82866 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (84): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (7): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2015 <- tri_data_2015 %>% 
  select()

library(readr)
tri_data_2016 <- read_csv("../data/2016_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 81598 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (85): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (6): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2016 <- tri_data_2016 %>% 
  select()

library(readr)
tri_data_2017 <- read_csv("../data/2017_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 81725 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (85): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (6): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2017 <- tri_data_2017 %>% 
  select()

library(readr)
tri_data_2018 <- read_csv("../data/2018_us.csv")
```

    ## Rows: 81510 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (85): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (6): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2018 <- tri_data_2018 %>% 
  select()

library(readr)
tri_data_2019 <- read_csv("../data/2019_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 80432 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (84): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (7): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2019 <- tri_data_2019 %>% 
  select()

library(readr)
tri_data_2020 <- read_csv("../data/2020_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 78051 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (84): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (7): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2020 <- tri_data_2020 %>% 
  select()

library(readr)
tri_data_2021 <- read_csv("../data/2021_us.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)

    ## Rows: 77515 Columns: 119
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (28): 2. TRIFD, 4. FACILITY NAME, 5. STREET ADDRESS, 6. CITY, 7. COUNTY,...
    ## dbl (84): 1. YEAR, 3. FRS ID, 10. BIA, 12. LATITUDE, 13. LONGITUDE, 19. INDU...
    ## lgl  (7): 21. PRIMARY SIC, 22. SIC 2, 23. SIC 3, 24. SIC 4, 25. SIC 5, 26. S...
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
tri_data_2021 <- tri_data_2021 %>% 
  select()
```

## 3. Ethics review

## 4. Data analysis plan
