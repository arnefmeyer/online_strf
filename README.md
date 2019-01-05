online_strf
===========

Description
-----------------
Python/C++ implementation of the methods described in

Arne F. Meyer, Jan-Philipp Diepenbrock, Frank W. Ohl, and Jörn Anemüller: [Fast and robust estimation of spectro-temporal receptive fields using stochastic approximations](http://dx.doi.org/10.1016/j.jneumeth.2015.02.009), Journal of Neuroscience Methods, Volume 246, 15 May 2015, Pages 119-133.

The code has been integrated into the [lnpy Python package](https://github.com/arnefmeyer/lnpy). Specifically, the stochastic gradient descent-based optimization methods (implemented in C++ via Cython) can be found [here](https://github.com/arnefmeyer/lnpy/blob/master/lnpy/learn/sgd.py). These are rather low-level routines and high-level wrappers are in the different subpackages, e.g., the [CbRF method](https://github.com/arnefmeyer/lnpy/blob/master/lnpy/lnb/cbrf.py) used in the paper.

