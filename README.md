<!-- rmarkdown v1 -->
<!-- README.md is generated from README.Rmd. Please edit that file -->

# fgm
An R Package for Performing **F**luvial **G**eo**M**orphology Analysis <img src="man/figures/castle.png" align="right" />

## Package Status
[![Maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle)
[![Project Status: Active The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![packageversion](https://img.shields.io/badge/Package%20version-0.1.9-orange.svg?style=flat-square)](commits/master)
[![Last-changedate](https://img.shields.io/badge/last%20change-2019--09--08-yellowgreen.svg)](/commits/master)
[![Licence](https://img.shields.io/badge/licence-CC0-blue.svg)](http://choosealicense.com/licenses/cc0-1.0/)

## Description
This package contains a wide range of functions for performing fluvial 
geomorphic analysis. This package is designed for use with the FluvialGeomorph 
Python package. The FluvialGeomorph package contains an ArcGIS toolbox that can 
be used to extract spatial data from high-resolution terrain data. 
FluvialGeomorph uses functions in this package to perform a wide range of 
fluvial geomorphic analysis:

* derive synthetic stream channel dimensions
* derive stream planform dimensions
* help choose a bankfull elevation for ungaged streams

## Funding
Funding for development and maintenance of `fgm` was provided by the US Army 
Corps of Engineers (USACE) [Ecosystem Management and Restoration
Research Program (EMRRP)](https://emrrp.el.erdc.dren.mil). <img src="man/figures/EMRRP_logo_300.png" align="right" />

## Authors
* Michael Dougherty, Geographer, U.S. Army Corps of Engineers
* Christopher Haring, Fluvial Geomorphologist/Research Physical Scientist, U.S. Army Corps of Engineers
* Charles Theiling, Ecologist, U.S. Army Corps of Engineers

## Install
To install the `fgm` package, install from GitHub using the `devtools` package:

```r
library(devtools)
install_github(repo = "mpdougherty/fgm", build_vignettes = TRUE)
```
