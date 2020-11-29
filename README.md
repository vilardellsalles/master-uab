# Practical class on optical photometry standardization 

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

* [`matplotlib`](https://matplotlib.org/) is a comprehensive library for
creating static, animated, and interactive visualizations in Python.
* [`ccdproc`](https://ccdproc.readthedocs.io/en/latest/) is a package
for basic data reductions of CCD images. It provides the essential tools for
processing of CCD images in a framework that provides error propagation and bad
pixel tracking throughout the reduction process.


## References

* [Python3](https://docs.python.org/3.8/).
* [Awesome Python](https://awesome-python.com/).
* [Learn Astropy](https://learn.astropy.org/tutorials.html).
* [Python for Astronomers and Particle Physicists](https://github.com/Python4AstronomersAndParticlePhysicists/PythonWorkshop-ICE).


