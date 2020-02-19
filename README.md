# Funclustering

[![Travis build status](https://travis-ci.com/modal-inria/Funclustering.svg?branch=master)](https://travis-ci.com/modal-inria/Funclustering) [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/modal-inria/Funclustering?branch=master&svg=true)](https://ci.appveyor.com/project/modal-inria/Funclustering)

[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/Funclustering)](https://cran.r-project.org/package=Funclustering) [![Total Downloads](http://cranlogs.r-pkg.org/badges/grand-total/Funclustering?color=blue)](http://cranlogs.r-pkg.org/badges/grand-total/Funclustering) [![Downloads](https://cranlogs.r-pkg.org/badges/Funclustering)](https://cran.rstudio.com/web/packages/Funclustering/index.html)

The code was originally on an [R-forge repository](https://r-forge.r-project.org/projects/soueidatt/).


This package proposes a model-based clustering algorithm for multivariate functional data. The parametric mixture model, based on the assumption of normality of the principal components resulting from a multivariate functional PCA, is estimated by an EM-like algorithm. The main advantage of the proposed algorithm is its ability to take into account the dependence among curves.


## Installation

From github:
```
library(devtools)
install_github("modal-inria/Funclustering")
```

## Credits

**Funclustering** is developed by Mohamed Soueidatt, Julien Jacques and Christophe Biernacki with contribution of Vincent Kubicki and Quentin Grimonprez

Copyright Inria - Université de Lille

## Licence

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
[GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.en.html) for more details.


## References

* J.Jacques and C.Preda (2013), Funclust: a curves clustering method using functional random variable density approximation, Neurocomputing, 112, 164-171.
* J.Jacques and C.Preda (2013), Model-based clustering of multivariate functional data, Computational Statistics and Data Analysis, in press DOI 10.1016/j.csda.2012.12.004.


