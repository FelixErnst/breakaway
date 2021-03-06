# breakaway <img src="man/figures/breakaway-logo.png" align="right" width="165px"/>

[![Travis-CI Build
Status](https://travis-ci.org/adw96/breakaway.svg?branch=master)](https://travis-ci.org/adw96/breakaway)
[![Coverage
status](https://codecov.io/gh/adw96/breakaway/branch/master/graph/badge.svg)](https://codecov.io/github/adw96/breakaway?branch=master)

`breakaway` is the premier package for statistical analysis of microbial
diversity. `breakaway` implements the latest and greatest estimates of
richness, as well as the most commonly used estimates. Understanding the
drivers of microbial diversity is an important frontier of microbial
ecology, and investigating the diversity of samples from microbial
ecosystems is a common step in any microbiome analysis.

[`DivNet`](https://github.com/adw96/DivNet) is a new package by the same
authors for estimating Shannon diversity, and other diversity indices.
`breakaway` focuses on richness while `DivNet` focuses on Shannon,
Simpson, and other alpha diversities as well as some beta diversity
indices. Check it out\!

`breakaway` has undergone substantial renovations to make it more
modern, easy-to-use, and robust. If functionality that you previously
enjoyed in `breakaway` no longer exists, please submit an
[issue](https://github.com/adw96/breakaway/issues)\!

### Citing breakaway

The `R` package `breakaway` implements a number of different richness
estimates. Please cite the following if you use them:

  - `breakaway()` and `kemp()`: Willis, A. & Bunge, J. (2015).
    Estimating diversity via frequency ratios. Biometrics.
  - `betta()`: Willis, A., Bunge, J., & Whitman, T. (2017). Improved
    detection of changes in species richness in high diversity microbial
    communities. JRSS-C.
  - `breakaway_nof1()`: Willis, A. (2016+). Species richness estimation
    with high diversity but spurious singletons. arXiv.
  - `objective_bayes_*()`: Barger, K. & Bunge, J. (2010). Objective
    Bayesian estimation for the number of species. Bayesian Analysis.

## Installation

You can install `breakaway` from github by running:

``` r
install.packages("devtools")
devtools::install_github("adw96/breakaway")
```

`breakaway` is actively maintained and continually expanding and
developing its scope\! Is there a method you would like to have
implemented in breakaway? Submit a pull request or contact the
[maintainer](http://statisticaldiversitylab.com/team/amy-willis)\!

### Documentation

  - The best place to start is the
    [vignettes](https://adw96.github.io/breakaway/articles/).
  - Documentation for functions can be found
    [here](https://adw96.github.io/breakaway/reference/index.html)
  - A pdf of all documentation can be found in the
    [breakaway-manual.pdf](https://github.com/adw96/breakaway/tree/master/breakaway-manual.pdf)
  - We try to answer frequently asked questions on the
    [wiki](https://github.com/adw96/breakaway/wiki)

## Humans

Maintainer: [Amy Willis](http://statisticaldiversitylab.com)

Authors: [Amy Willis](http://statisticaldiversitylab.com), [Bryan
Martin](https://bryandmartin.github.io/), [Pauline
Trinh](https://twitter.com/paulinetrinh), [Kathryn
Barger](http://hnrca.tufts.edu/kathryn-barger-ph-d/) and [John
Bunge](https://stat.cornell.edu/people/faculty/john-bunge)

Do you have a request for us? Let us know\! We want folks to use
`breakaway` and are committed to making it as easy to use as possible.

Do you have a question? Check out the
[wiki](https://github.com/adw96/breakaway/wiki), then shoot us an email.
We receive a lot of emails from users, so we try to answer questions on
the Wiki rather than responding to everyone individually.
