
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tekton

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Check
accessibility](https://img.shields.io/badge/check-accessibility-orange.svg)](https://wave.webaim.org/report#/https://packages.tesselle.org/tekton)
<!-- badges: end -->

**tekton** provides a custom [**pkgdown**](https://pkgdown.r-lib.org/)
template for [tesselle](https://www.tesselle.org) packages. Please don’t
use it for your own package.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("tesselle/tekton")
```

## Usage

Make sure your `_pkgdown.yaml` contains:

``` yaml
template:
  package: tekton
```

To work properly, `tekton` requires the assets and templates in
`inst/pkgdown/assets/`. Because of this, you should not set
`default_assets: false` in your `_pkgdown.yaml`.
