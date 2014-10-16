# BIOMD0000000202: ChenXF2008_CICR

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000202.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000202.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000202 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


The model reproduces the plots in Figures 1 and 2. Note that the units of the
time scale "A" are not right in the paper, it was corrected by the curator.
Model successfully tested on MathSBML.


