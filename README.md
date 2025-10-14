## eiExpand

eiExpand augments the 'eiCompare' package's Racially Polarized Voting (RPV) functionality to streamline analyses and visualizations used to support voting rights and redistricting litigation. The package implements methods, such as performance analysis, described in Barreto, M., Collingwood, L., Garcia-Rios, S., & Oskooii, K. A. (2022). "Estimating Candidate Support in Voting Rights Act Cases: Comparing Iterative EI and EI-R×C Methods" <doi:10.1177/0049124119852394>.

This is primarily intended for users of eiCompare to utilize the additional functionality provided by this package's functions.

Full references, albeit for 1.0.5 are included on Cran https://cran.r-project.org/web/packages/eiExpand/eiExpand.pdf. The current Github version does not have RPV_toDF() or rpv_coef_plot()

## News

### eiExpand 1.0.6, October 14, 2025

#### Package changes

* Two functions - RPV_toDF() and rpv_coef_plot() - were moved into eiCompare and removed from eiExpand to prevent duplicates.

## Installation

### From CRAN

CRAN submission update is in process. The current CRAN version is not up to date. Check back soon for instructions on installation from CRAN.

### From Github (development version)

Install latest development version with:

```
remotes::install_github('RPVote/eiExpand')
```
