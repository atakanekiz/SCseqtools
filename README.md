

```{r}

if (!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")

devtools::install_github("atakanekiz/SCseqtools", build_vignettes = TRUE)

# # For faster installation without vignette
# devtools::install_github("atakanekiz/SCseqtools", build_vignettes = FALSE)

```
