# Filament Detection
[![DOI](https://zenodo.org/badge/1078394794.svg)](https://doi.org/10.5281/zenodo.21146399) [![arXiv](https://img.shields.io/badge/arXiv-preprint-b31b1b.svg)](https://arxiv.org/pdf/2510.263189)

## Overview
This repository provides the filament detection code used to produce the results presented in the [paper](https://arxiv.org/pdf/2510.26318)

## Dataset 
We provide a reduced version of the [shear catalog](https://github.com/rahulshinde98/filament-detection/edit/main/shear_catalog.csv) for the Abell 2029 system, containing galaxy positions and shear measurements. A [FITS header file](https://github.com/rahulshinde98/filament-detection/edit/main/image_header.fits) corresponding to the FITS image used in the analysis is provided to facilitate astrometric conversions. [A NumPy file](https://github.com/rahulshinde98/filament-detection/edit/main/stdev_T_LSS_array_A2029.npy) provides the large-scale structure (LSS) induced standard deviation in the tangential statistic, estimated separately from mock simulations. This is used to evaluate the SNR of the filament signal. 

## Code 
We provide a [jupyter notebook](https://github.com/rahulshinde98/filament-detection/edit/main/filament_detection_example.ipynb) that presents the filament detection analysis and corresponding results for the Abell 2029 system. The [requirements file](https://github.com/rahulshinde98/filament-detection/edit/main/requirements.txt) lists all dependencies required to run the notebook. 


## Attribution
If you use this work, please cite the following paper: [Shinde and Dell’Antonio (2025)](https://arxiv.org/abs/2510.26318).

The corresponding BibTeX entry is provided below: 

```bibtex
@ARTICLE{fil-detection,
       author = {{Shinde}, Rahul and {Dell'Antonio}, Ian},
        title = "{Weak-Lensing Detection of Intercluster Filaments in Three Nearby Cluster Systems}",
      journal = {arXiv e-prints},
     keywords = {Cosmology and Nongalactic Astrophysics},
         year = 2025,
        month = oct,
          eid = {arXiv:2510.26318},
        pages = {arXiv:2510.26318},
          doi = {10.48550/arXiv.2510.26318},
archivePrefix = {arXiv},
       eprint = {2510.26318},
 primaryClass = {astro-ph.CO},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2025arXiv251026318S},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
