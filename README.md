# Bachelor's Thesis — R Analysis

R code for the empirical analysis in my bachelor's thesis:
**"Power and Sample Size Determination for Randomization Tests in Covariate Adjusted Experiments"**

## Data
LaLonde (1986) experimental sample via the `Matching` package in R (`data(lalonde)`).

## Requirements
```r
install.packages(c("tidyverse", "Matching"))
```

## Contents
`Chapter4.Rmd` — FWL residualization, permutation tests, power analysis, 
sensitivity analysis, and all figures for the thesis.
