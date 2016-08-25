# scipy-lsq_linear

lsq_linear is implementation of scipy.optimze.lsq_linear for old scipy version.

## Setup

`pip install git+https://github.com/xica/scipy-lsq_linear`

## Usage

`lsq_linear.lsq_linear` has the same interface as `scipy.optimeze.lsq_linear` except that our function accepts only `bvls` method.

This is because this library include only pure python script (`trf` method uses Cython module).

See the official documentation:
http://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.lsq_linear.html
