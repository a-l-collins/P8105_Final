ainsel weather
================
Ainsel Levitskaia-Collins, HL2710
2025-11-18

- [x] find weather data
- [x] find holiday data
- [x] import gun data
- [x] import weather data
- [ ] import holiday data
- [ ] tidy datasets
- [ ] initial analyses

notes:

- make sure to filter shooting data by incident key, to not have
  unintentional duplicates

``` r
shooting_h <- read_csv("./Data Folder/Shooting_Historic.csv")
shooting_2025 <- read_csv("./Data Folder/Shooting_2025.csv")
weather <- read_csv("./Data Folder/Weather.csv")
```

    ## Warning: One or more parsing issues, call `problems()` on your data frame for details,
    ## e.g.:
    ##   dat <- vroom(...)
    ##   problems(dat)
