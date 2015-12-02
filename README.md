# drat [IN DEVELOPMENT]
The `R` package `drat` enables `github` to behave as an `R` repository that allows the use of `install.packages()`.
This latter function checks for and automatically installs package dependencies.

To use:
```{r}
drat::addRepo("OHDSI")
install.packages("PatientLevelPrediction", type = "source")
```
