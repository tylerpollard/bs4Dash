# bs4Dash <img src="https://rinterface.com/inst/images/bs4Dash.svg" width="200px" align="right"/>

[![R build status](https://github.com/RinteRface/bs4Dash/workflows/R-CMD-check/badge.svg)](https://github.com/RinteRface/bs4Dash/actions)
[![version](http://www.r-pkg.org/badges/version/bs4Dash)](https://CRAN.R-project.org/package=bs4Dash)
[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-ff69b4.svg)](https://www.tidyverse.org/lifecycle/#maturing)
[![cranlogs](https://cranlogs.r-pkg.org/badges/bs4Dash)](https://CRAN.R-project.org/package=bs4Dash)
[![total](https://cranlogs.r-pkg.org/badges/grand-total/bs4Dash)](https://www.rpackages.io/package/bs4Dash)
[![Codecov test coverage](https://codecov.io/gh/RinteRface/bs4Dash/branch/master/graph/badge.svg)](https://codecov.io/gh/RinteRface/bs4Dash?branch=master)

> Bootstrap 4 shinydashboard using [AdminLTE3](https://github.com/ColorlibHQ/AdminLTE)

<br>

<div class="row">
<div class="col-sm-6" align="center">
<div class="card">
<a href="https://dgranjon.shinyapps.io/virtual_patient_v2/" target="_blank"><img src="https://community.rstudio.com/uploads/default/original/2X/e/eb1013fd09ccf10cbe13da3f0168eebfcb0eba75.gif"></a>
</div>
</div>
</div>

<br>

See a working example on shinyapps.io [here](https://dgranjon.shinyapps.io/bs4DashDemo/).

## Useful Informations (if any)

Recent breaking change in dev version: _label_ becomes _cardLabel_ in `bs4Card()`!

## Installation

This package is on CRAN:

```r
# from CRAN
install.packages("bs4Dash")
# latest devel version
devtools::install_github("RinteRface/bs4Dash")
```

## Demo

See a preview of the package [here](https://rinterface.com/shiny/bs4Dash/classic/) and
[here](https://rinterface.com/shiny/bs4Dash/old_school/) or run

```r
library(bs4Dash)
# classic theme
bs4DashGallery()
# old_school theme
bs4DashGallery(theme = "old_school")
```

An applied example can be found [here](https://rinterface.com/shiny/showcase/ratp/) (the 
original dashboard was made by [Philippine Rheins](https://twitter.com/PhilippineRs) 
from [dreamRs](https://twitter.com/dreamRs_fr)).

## Issues

Issues are listed [here](https://github.com/RinteRface/bs4Dash/issues). 


## Acknowledgement

I warmly thank [Glyphicons](https://www.glyphicons.com) creator for providing them for free with Bootstrap. 

## Code of Conduct
  
  Please note that the bs4Dash project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.
