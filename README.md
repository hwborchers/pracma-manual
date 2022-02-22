# R Package pracma Manual

The *pracma* packege provides a large number of functions from 
numerical analysis and linear algebra, numerical optimization, 
differential equations, time series, plus some well-known special 
mathematical functions.  
Uses 'MATLAB' function names where appropriate to simplify porting.

The [pracma Manual](http://htmlpreview.github.io/?https://github.com/hwborchers/pracma-manual/blob/master/index.html)
has been generated from the help pages of *pracma* with the help of 
the *pkgdown*.


## NEWS in 2020-2022

- Added lu_crout(), Crout's algorithm for LU matrix decomposition
- Function deeve() requires the x-coordinates to be sorted
- Allow for complex matrices in pinv() (and mldivide())
- Small correction in movavg(): default type now is 's'
- ellipke() help page: compute the circumference of an ellipse
- circlefit(): option 'fast' is deprecated and will not be used

## DESCRIPTION File

```
Package: pracma
Type: Package
Version: 2.1.6
Date: 2018-08-30
Title: Practical Numerical Math Functions
Authors@R: person("Hans W.", "Borchers", 
                  email="hwborchers@googlemail.com", 
                  role=c("aut", "cre"))
Depends: R (>= 3.1.0)
Imports: graphics, grDevices, stats, utils
Suggests: quadprog
Description:
    Provides a large number of functions from numerical analysis and
    linear algebra, numerical optimization, differential equations,
    time series, plus some well-known special mathematical functions.
    Uses 'MATLAB' function names where appropriate to simplify porting.
License: GPL (>= 3)
ByteCompile: true
LazyData: yes
```

