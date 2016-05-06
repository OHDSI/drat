# drat repository for OHDSI R packages
The `R` package `drat` enables `github` to behave as an `R` repository that allows the use of `install.packages()`.
This latter function checks for and automatically installs package dependencies.

To use:
```{r}
install.packages("drat")
drat::addRepo("OHDSI")   ## Could place in ~/.Rprofile
install.packages("PatientLevelPrediction", type = "source") ## Automatically installs dependencies
```
