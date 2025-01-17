
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- used devtools::build_readme() to update the md -->
<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/rnaturalearth)](https://CRAN.R-project.org/package=rnaturalearth)
[![](https://badges.ropensci.org/22_status.svg)](https://github.com/ropensci/software-review/issues/22)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![R-CMD-check](https://github.com/ropensci/rnaturalearth/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/ropensci/rnaturalearth/actions/workflows/R-CMD-check.yaml)

<!-- badges: end -->

# rnaturalearth

An R package to hold and facilitate interaction with [Natural
Earth](https://www.naturalearthdata.com/) map data.

This package provides :

- access to a pre-downloaded subset of Natural Earth v4.1.0 (March 2018)
  vector data commonly used in world mapping

- easy subsetting by countries and regions

- functions to download other Natural Earth vector and raster data

- a simple, reproducible and sustainable workflow from Natural Earth
  data to rnaturalearth enabling updating as new versions become
  available

- clarification of differences in world maps classified by countries,
  sovereign states and map units

- consistency with Natural Earth naming conventions so that
  rnaturalearth users can use Natural Earth documentation

- data in ‘sf’ or ‘sp’ formats

The [Natural Earth](https://www.naturalearthdata.com/) website
structures vector data by scale, category and type. These determine the
filenames of downloads. rnaturalearth uses this structure to facilitate
download (like an API).

## Install rnaturalearth

Install from CRAN :

``` r
install.packages("rnaturalearth")
```

or install the development version from GitHub using
[devtools](https://github.com/r-lib/devtools).

``` r
devtools::install_github("ropensci/rnaturalearth")
```

Data to support much of the package functionality are stored in two data
packages that you will be prompted to install when required if you do
not do so here.

``` r
devtools::install_github("ropensci/rnaturalearthdata")
devtools::install_github("ropensci/rnaturalearthhires")
```
