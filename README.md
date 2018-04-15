# Dataset for &ldquo;Lattice-Geometry Effects in Garnet Solid Electrolytes: A Lattice-Gas Monte Carlo Simulation Study&rdquo;

[![DOI](https://zenodo.org/badge/93930678.svg)](https://zenodo.org/badge/latestdoi/93930678)
[![LICENSE](https://img.shields.io/badge/LICENSE-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![ARXIV](https://img.shields.io/badge/arXiv-1707.00491-yellow.svg)](https://arxiv.org/abs/1707.00491)
[![RSOS](https://img.shields.io/badge/manuscript%20DOI-10.1098%2Frsos.170824-yellow.svg)](http://dx.doi.org/10.1098/rsos.170824)
[![CircleCI](https://circleci.com/gh/bjmorgan/garnet-lgmc-data.svg?style=shield&circle-token=8df28629ca7292fec637a6b48e16658bac41ae8f)](https://circleci.com/gh/bjmorgan/garnet-lgmc-data)

[Benjamin J. Morgan.](http://orcid.org/0000-0002-3056-8233)

This repository contains lattice-gas Monte Carlo simulation data and supporting code for the paper &ldquo;[Lattice-Geometry Effects in Garnet Solid Electrolytes: A Lattice-Gas Monte Carlo Simulation Study](http://dx.doi.org/10.1098/rsos.170824)&rdquo; [1].

The repository contains:
1. the complete data set used to support the findings of the study.
2. example scripts for running [`lattice_mc`](http://joss.theoj.org/papers/6940b7bb0d59be86b8823a10780caae0) simulations on a garnet lattice, and collating the output data.
3. a [Jupyter notebook](analysis/garnet_LGMC.ipynb) containing the code used to generate Figures 2&ndash;A4 in the manuscript.

## [Simulations](simulations)

Example scripts for running lattice-gas Monte Carlo simulations on a garnet lattice. These scripts use the [`lattice_mc`](http://joss.theoj.org/papers/6940b7bb0d59be86b8823a10780caae0) lattice-gas Monte Carlo code. Full details are given in the [`README.md`](simulations/README.md).

## [Data](data)

The complete data set produced for this study.

## [Analysis](analysis)

A [Jupyter notebook](analysis/garnet_LGMC.ipynb) containing all numerical analysis presented in the manuscript, and code to generate Figs. 2&ndash;A4.

## [Figures](figures)
PDF versions of the figures generated by the analysis notebook.

## Citing this dataset

Cite as:

Morgan, Benjamin J. (2017, July 2). Dataset for "Lattice-Geometry Effects in Garnet Solid Electrolytes: A Lattice-Gas Monte Carlo Simulation Study". Zenodo. http://doi.org/10.5281/zenodo.821864.

### BibTeX

```
@misc{morgan_benjamin_j_2017_821864,
  author       = {Morgan, Benjamin J.},
  title        = {{Dataset for "Lattice-Geometry Effects in Garnet 
                   Solid Electrolytes: A Lattice-Gas Monte Carlo
                   Simulation Study"}},
  month        = jul,
  year         = 2017,
  doi          = {10.5281/zenodo.821864},
  url          = {https://doi.org/10.5281/zenodo.821864}
}
```

## Acknowledgements
B. J. M. acknowledges support from the Royal Society (UF130329).

## References

1. B. J. Morgan *Lattice-Geometry Effects in Garnet Solid Electrolytes: A Lattice-Gas Monte Carlo Simulation Study*. [R. Soc. open sci. 4: 170824. (2017)](http://dx.doi.org/10.1098/rsos.170824).

