# Photon-HDF5 Online Converter

This is a demo service to convert data files to [Photon-HDF5](www.photon-hdf5.org) 
without the need to install any software. Currently, input data files 
cannot be larger than 35 MB.

The supported file formats are PicoQuant **HT3**, Becker & Hickl **SPC/SET** and 
the custom format **SM** (a format formerly used in Weiss Lab).
For each supported file format we provide a Jupyter notebook that
contains both the instructions and the code to convert the file.

To launch the demo click on the following button:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/Photon-HDF5/Photon-HDF5-Converter)

For instructions on *how to use the notebook interface* see [this page](http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb#The-Notebook-dashboard). For an overview of what *Jypyter Notebook* is refer to this
[nature paper](http://www.nature.com/news/interactive-notebooks-sharing-the-code-1.16261),
and to the [Jupyter Project Homepage](https://jupyter.org/).

# Install the converter locally

Under the hood this demo service runs the phconvert software.
You can install phconvert on you own desktop following the
instructions in the [phconvert homepage](http://photon-hdf5.github.io/phconvert/).

# Feedback

For questions or comments please:

- [Open an GitHub issue](https://github.com/Photon-HDF5/phconvert/issues) or
- Ask a question on the [Photon-HDF5 Google Group](https://groups.google.com/forum/#!forum/photon-hdf5).

# How this demo was built?

This online demo uses [MyBinder.org](http://mybinder.org/) to run the
Jupyter notebooks included with [phconvert](http://photon-hdf5.github.io/phconvert/). 
Many thanks to [Jeremy Freeman](http://www.jeremyfreeman.net/) 
and collaborators for providing this amazing service.

