# Segmenting synchrotron x-radiographs with scikit-image

Materials presented at the ['Machine Learning for Synchrotrons'
workshop](https://als.lbl.gov/2021-user-meeting-workshops-tutorials/) of the
2021 ALS User Meeting.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mkcor/als-ml-sync.git/main?urlpath=%2Fvoila%2Frender%2Fslideshow.ipynb) (view Voilà slideshow)

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/mkcor/als-ml-sync/main?filepath=slideshow.ipynb) (run Jupyter notebook)

## Setup

Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or
[Mambaforge](https://github.com/conda-forge/miniforge#mambaforge).

    $ mamba env create -f environment.yml
    $ conda activate als-ml-sync
    $ voila --strip_sources=False --template=reveal slideshow.ipynb

## References

* https://github.com/cgusb/solidification-tracking
