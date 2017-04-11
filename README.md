# dtq
Dtq assignment

Cleaned input datasets are too large but there are shell commands in the Rmd file to generate them. I provide them here as well:
```
grep -v "?" census_income_learn.csv > census_income_learn_nomiss.csv
grep -v "?" census_income_test.csv > census_income_test_nomiss.csv
```
