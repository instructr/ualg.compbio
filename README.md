
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ualg.compbio

<!-- badges: start -->
<!-- badges: end -->

The goal of `{ualg.compbio}` is to provide the teaching materials for
the Computational Biology classes at UAlg, part of the curriculum of the
Masters in Biomedical Sciences.

## Installation

Make sure you have the `{remotes}` installed:

``` r
install.packages('remotes')
```

Now you can install `{ualg.compbio}` from [GitHub](https://github.com/)
with:

``` r
# install.packages("remotes")
remotes::install_github("instructr/ualg.compbio")
```

## Tutorials

To list the included tutorials in `{ualg.compbio}`:

``` r
learnr::available_tutorials(package = 'ualg.compbio')
#> Available tutorials:
#> * ualg.compbio
#>   - self_eval_exam  : "Self Evaluation Exam 1 | Biologia Computacional 2022"
#>   - transcriptomics : "Transcriptomics tutorial | Biologia Computacional 2022"
```

To run one of the tutorials included in `{ualg.compbio}` use the command
`learnr::run_tutorial()`. For example to run the interactive tutorial
`"self_eval_exam"`:

``` r
learnr::run_tutorial('self_eval_exam', package = 'ualg.compbio')
```

To run the tutorial `"transcriptomics"`:

``` r
learnr::run_tutorial('transcriptomics', package = 'ualg.compbio')
```
