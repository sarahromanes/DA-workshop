
DA workshop for USYD Bioinformatics Group 
======================================================

Learning about the `multiDA` and `genDA` packages.


Overview
--------

In this workshop, we will very quickly be introduced to the following two packages for modern discriminant analyis techniques - `multiDA` and `genDA`. These packages are a suite of discriminant analysis packages I have authored for large-scale/complex datasets.  

[**multiDA**](https://github.com/sarahromanes/multiDA) is a Discriminant Analysis (DA) algorithm capable for use in high dimensional datasets, providing feature selection through multiple hypothesis testing. This algorithm has minimal tuning parameters, is easy to use, and offers improvement in speed compared to existing DA classifiers.
*Publication available from the Journal of Computational and Graphical Statistics, [here](https://www.tandfonline.com/doi/full/10.1080/10618600.2019.1637748).*

[**genDA**](https://github.com/sarahromanes/genDA) is a Discriminant Analysis (DA) algorithm capable for use in multi-distributional response data - generalising the capabilities of DA beyond Gaussian response. It utilises *Generalised Linear Latent Variable Models (GLLVMs)* to capture the covariance structure between the different response types and provide an efficient classifier for such datasets. This package leverages the highly resourceful [TMB](https://github.com/kaskr/adcomp/wiki) package for fast and accurate gradient calculation in `C++`.
*This work was presented at ACEMS - Enabling Algorithms Symposium in June, 2019. See a run down of the mathematics behind this package [here](https://sarahromanes.github.io/talks/ACEMS/ACEMS_SarahRomanes.pdf).*

Slides summarising both these packages, given at **useR!2019** can be found [here](https://sarahromanes.github.io/talks/useR2019/).


Installation
--------

```r
# Install the development version from GitHub:
# install.packages("devtools")
devtools::install_github("sarahromanes/multiDA")

```

```r
# Install the development version from GitHub:
# install.packages("devtools")
devtools::install_github("sarahromanes/genDA")

```

## Authors

* **Sarah Romanes**  - [@sarah_romanes](https://twitter.com/sarah_romanes)
* **John Ormerod**   - [@john_t_ormerod](https://twitter.com/john_t_ormerod)

## Contribute!!

If you find any issues with my packages, or can offer suggestions for improvement, please post them at the corresponding issue tabs.
