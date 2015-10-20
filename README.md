# Regularized Regression
mock example for science forum


**glmnet** is R packeage written by Jerome Friedman, Trevor Hastie, Noah Simon, and Rob Tibshirani that allows for easy application of regularized generalized linear models to data.  

### Theoretical background on regularized regression and glmnet tutorials can be found below:
* [Ridge Regression: Biased Estimation for Nonorthogonal Problems](http://math.arizona.edu/~hzhang/math574m/Read/Ridge.pdf)  (Hoerl and Kennard 1970)
* [Regression Shrinkage and Selection via the Lasso](http://statweb.stanford.edu/~tibs/lasso/lasso.pdf) (Tibshirani 1996)
* Additional theoretical and intuition background available from [Elements of Statisitcal Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/) (Hastie, Tibshirani, and Friedman) and [Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Fourth%20Printing.pdf) (James, Witten, Hastie, and Tibshirani) 
* **glmnet** tutorial [glmnet Vignette](https://web.stanford.edu/~hastie/glmnet/glmnet_alpha.html) (Hastie and Qian) 

### Installing the package

* Stable version on CRAN:

```s
install.packages("LDAvis")
```

* Development version on GitHub (with [devtools](http://cran.r-project.org/web/packages/devtools/index.html)):

```s
devtools::install_github("cpsievert/LDAvis")
```

### Getting started

Once installed, we recommend a visit to the main help page:

```s
library(LDAvis)
help(createJSON, package = "LDAvis")
```
