# Filament Detection
## Overview
This repository provides the filament detection code used to produce the results presented in the [paper](https://arxiv.org/pdf/2510.26318)

## Dataset 
We provide a reduced version of the [shear catalog](https://github.com/rahulshinde98/filament-detection/edit/main/shear_catalog.csv) for the Abell 2029 system, containing galaxy positions and shear measurements. A [FITS header file](https://github.com/rahulshinde98/filament-detection/edit/main/image_header.fits) corresponding to the FITS image used in the analysis is also provided. 

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
