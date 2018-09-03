# R Package pracma

The *pracma* packege provides a large number of functions from 
numerical analysis and linear algebra, numerical optimization, 
differential equations, time series, plus some well-known special 
mathematical functions.  
Uses 'MATLAB' function names where appropriate to simplify porting.

The [pracma Manual](http://htmlpreview.github.io/?https://github.com/hwborchers/pracma-manual/blob/master/index.html)
has been generated from the help pages of *pracma* with the help of 
the *pkgdown*.


## NEWS in 2018

- Si(), Ci() sine and cosine integral functions added.
- Added dot notation for brent(), bisect(), newton(), halley(), and 
  ridders() on request of John Nash for the histoRicalg project.

- shubert() implements one-dimensional Shubert-Piyavskii method.
- fminsearch() and anms() stop for one-dimensional minimization.

- bsxfun() now uses sweep() for matrices in search of higher speed.
- direct1d() removed because slow and not effective.

- poisson2disk() approximate Poisson disk distribution
- Corrected small bug in findpeaks(), reported by Mike Badescu.


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

