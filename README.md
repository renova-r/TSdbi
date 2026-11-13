# TSdbi

A common R interface to time series databases, with S4 generics for retrieving, storing and documenting series and their vintages.

Compatibility updates by Renova.

Version 2017.4.1.9001 turns Rd cross-references to optional, uninstalled packages (`TSSQLite`, `TSMySQL`, `TSPostgreSQL`, `tframePlus`) into plain text so help links resolve, and adds an `Authors@R` entry equivalent to the existing author and maintainer. No R code was changed.

## Install

```r
install.packages("TSdbi", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/TSdbi@renova-2017.4.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

TSdbi is by Paul Gilbert (maintainer); copyright 2007-2011 Bank of Canada and 2012-2017 Paul Gilbert. The original project is at <http://tsdbi.r-forge.r-project.org/>. License: GPL-2; see [COPYING](COPYING).
