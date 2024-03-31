
<!-- README.md is generated from README.Rmd. Please edit that file -->

# talaan: An Interface to the Philippine Civil Registration and Vital Statistics Data

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/panukatan/talaan/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/panukatan/talaan/actions/workflows/R-CMD-check.yaml)
[![test-coverage](https://github.com/panukatan/talaan/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/panukatan/talaan/actions/workflows/test-coverage.yaml)
[![Codecov test
coverage](https://codecov.io/gh/panukatan/talaan/branch/main/graph/badge.svg)](https://app.codecov.io/gh/panukatan/talaan?branch=main)
[![CodeFactor](https://www.codefactor.io/repository/github/panukatan/talaan/badge)](https://www.codefactor.io/repository/github/panukatan/talaan)
<!-- badges: end -->

The Philippine Statistics Authority (PSA) makes civil registration data
publicly available through their monthly updates on numbers of births,
deaths, and marriages released via their website. This package provides
utilities for accessing and processing the civil registration and vital
statistics data released by the PSA.

## What does `talaan` do?

Please note that `talaan` is still highly experimental and is undergoing
a lot of development. Hence, any functionalities described below and in
the rest of the package documentation have a high likelihood of changing
interface or approach as we aim for a stable working version.

Currently, the package provides the following functionalities:

### Monthly update releases

- Retrieval and/or download of monthly civil registry and vital
  statistics updates released by the PSA on their website;

- Standardised naming of civil registry and vital statistics release
  files;

- Upload and/or archive raw monthly civil registry and vital statistics
  releases onto specific platforms; and,

- Process monthly civil registry and vital statistics releases into
  machine-readable and relational database-ready structures.

### Historical/archived datasets

- Retrieval and/or download of historical/archived civil registry and
  vital statistics datasets made available on the PSA website;

- Standardised naming of civil registry and vital statistics
  historical/archived files;

- Upload and/or archive raw historical civil registry and vital
  statistics datasets onto specific platforms; and,

- Process historical/archived civil registry and vital statistics
  datasets into machine-readable and relational database-ready
  structures.

## Installation

`talaan` is not yet on CRAN but can be installed from the [panukatan R
universe](https://panukatan.r-universe.dev) as follows:

``` r
install.packages(
  "talaan",
  repos = c('https://panukatan.r-universe.dev', 'https://cloud.r-project.org')
)
```

## Usage

## Citation

If you find the `talaan` package useful please cite using the suggested
citation provided by a call to the `citation()` function as follows:

``` r
citation("talaan")
#> To cite talaan in publications use:
#> 
#>   Ernest Guevarra (2024). talaan: An Interface to the Philippine Civil
#>   Registry and Vital Statistics Data R package version 0.0.0.9000 URL
#>   https://panukatan.io/talaan/
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {talaan: An Interface to the Philippines Civil Registry and Vital Statistics Data},
#>     author = {{Ernest Guevarra}},
#>     year = {2024},
#>     note = {R package version 0.0.0.9000},
#>     url = {https://panukatan.io/talaan/},
#>   }
```

## Community guidelines

Feedback, bug reports and feature requests are welcome; file issues or
seek support [here](https://github.com/panukatan/talaan/issues). If you
would like to contribute to the package, please see our [contributing
guidelines](https://panukatan.io/talaan/CONTRIBUTING.html).

This project is released with a [Contributor Code of
Conduct](https://panukatan.io/talaan/CODE_OF_CONDUCT.html). By
participating in this project you agree to abide by its terms.
