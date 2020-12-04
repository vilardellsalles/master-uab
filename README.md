# Practical class on optical photometry standardization 

This repository contains material for the practical class of the [Observational 
Techniques](https://guies.uab.cat/guies_docents/public/portal/html/2019/assignatura/42866/en) 
subject in the [High Energy Physics, Astrophysics and 
Cosmology](https://www.uab.cat/web/estudiar/official-master-s-degrees/general-information-1096480962610.html?param1=1345648395535)
master course at the [UAB](https://www.uab.cat/web/universitat-autonoma-de-barcelona-1345467954774.html).
The topics covered in this class should be considered a quick introduction to 
the several topics described and, therefore, some of the details required for 
an accurate data reduction have been excluded. 

The main goal of the current practical class is to compute standard photometry
from a set of raw science images. Images used in the current class are
[M67](http://simbad.u-strasbg.fr/simbad/sim-basic?Ident=m67) images obtained
with the [Wide Field Camera at the 2.5 meter Isaac Newton
Telescope](http://www.ing.iac.es/astronomy/instruments/wfc/). Two filters were
used for the observations: [Strömgren
b](http://svo2.cab.inta-csic.es/svo/theory/fps3/index.php?id=INT/WFC.Strom_b&&mode=browse&gname=INT&gname2=WFC#filter)
and [Strömgren
y](http://svo2.cab.inta-csic.es/svo/theory/fps3/index.php?id=INT/WFC.Strom_y&&mode=browse&gname=INT&gname2=WFC#filter).

The class is divided in the following blocks:

* [Introduction](notebooks/introduction.ipynb).
* [Image cleaning](notebooks/ccdred.ipynb).
* [Astrometry and photometry extraction](notebooks/photutils.ipynb).
* [Transformation to standard magnitudes](notebooks/standard.ipynb).

In order to follow the class, the required Python3 modules have to be installed.
They can be installed with
[Anaconda](https://docs.anaconda.com/anaconda/user-guide/) or from
[Pypi](https://pypi.org/). In this case, the packages to be installed are:

* [`numpy`](https://numpy.org/). Numpy is the fundamental package for scientific
computing with Python.
* [`scipy`](https://docs.scipy.org/doc/scipy/reference/). SciPy is an 
open-source software for mathematics, science, and engineering. It provides 
tools to work with Fourier transformations, polynomials, regressions, ...
* [`matplotlib`](https://matplotlib.org/). Matplotlib is a comprehensive
library for creating static, animated, and interactive visualizations in Python.
* [`ipympl`](https://github.com/matplotlib/ipympl). Leveraging the Jupyter
interactive widgets framework, ipympl enables the interactive features of
matplotlib in the Jupyter notebook and in JupyterLab.
* [`astropy`](https://docs.astropy.org/en/stable/index.html). The Astropy 
package contains key functionality and common tools needed for performing 
astronomy and astrophysics with Python.
* [`ccdproc`](https://ccdproc.readthedocs.io/en/latest/). Ccdproc is an 
[Astropy](https://docs.astropy.org/en/stable/index.html) affiliated package for
basic data reductions of CCD images. It provides the essential tools for 
processing of CCD images in a framework that provides error propagation and bad 
pixel tracking throughout the reduction process.
* [`photutils`](https://photutils.readthedocs.io/en/stable/). Photutils is an 
[Astropy](https://docs.astropy.org/en/stable/index.html) 
affiliated package that primarily provides tools for detecting and performing 
photometry of astronomical sources.
* [`astroquery`](https://astroquery.readthedocs.io/en/latest/). Astroquery is a
set of tools for querying astronomical web forms and databases.

## References

* [Python3](https://docs.python.org/3.8/).
* [Awesome Python](https://awesome-python.com/).
* [Learn Astropy](https://learn.astropy.org/tutorials.html).
* [Python for Astronomers and Particle 
Physicists](https://github.com/Python4AstronomersAndParticlePhysicists/PythonWorkshop-ICE).
