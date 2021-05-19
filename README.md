# CSR2D

This package computes the 2D CSR potential and wake functions defined in "Y. Cai and Yuantao. Ding, PRAB 23, 014402 (2020)". We aim to speed up the wake computation using numerical 2D convolution methods.

The required python packages are "mpmath" and "scipy". To use GPU, "cupy" needs to be installed too.


# Conda environment

```bash
conda env create -f environment.yml
conda activate csr2d
```


