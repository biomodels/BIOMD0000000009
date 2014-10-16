# BIOMD0000000009: BIOMD0000000009

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000009.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000009.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000009 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Huang1996 - Ultrasensitivity in MAPK cascade

The temporal sequence of kinase activation, from MAPKKK (activated RAF) to the
final effector MAPK (activated ERK), is described here. It is observed from
the model that there is an increase in sensitivity along the levels of the
cascade, where the activity of MAPK reaches its maximal before MAPKKK.

This model is described in the article:

[Ultrasensitivity in the mitogen-activated protein kinase
cascade.](http://identifiers.org/pubmed/8816754)

Huang CY, Ferrell JE Jr

Proc. Natl. Acad. Sci. U.S.A. 1996:93(19):10078-83

Abstract:

The mitogen-activated protein kinase (MAPK) cascade is a highly conserved
series of three protein kinases implicated in diverse biological processes.
Here we demonstrate that the cascade arrangement has unexpected consequences
for the dynamics of MAPK signaling. We solved the rate equations for the
cascade numerically and found that MAPK is predicted to behave like a highly
cooperative enzyme, even though it was not assumed that any of the enzymes in
the cascade were regulated cooperatively. Measurements of MAPK activation in
Xenopus oocyte extracts confirmed this prediction. The stimulus/response curve
of the MAPK was found to be as steep as that of a cooperative enzyme with a
Hill coefficient of 4-5, well in excess of that of the classical allosteric
protein hemoglobin. The shape of the MAPK stimulus/ response curve may make
the cascade particularly appropriate for mediating processes like mitogenesis,
cell fate induction, and oocyte maturation, where a cell switches from one
discrete state to another.

The species K_PP_norm, KKK_P_norm and KK_PP_norm are the relative
concentrations of the active MAPK, MAPKK and MAPKKK, that is the double, or
single resp. phophorylated forms divided by the total concentrations of each
kinase. For MAPK additionally the also active MAPK divided by the maximal
concentration of active MAPK is given by rel_K_PP_max. The parameter
K_PP_norm_max, the maximal ratio of active MapK, has to be calculated for each
change of parameters.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000009](http://identifiers.org/biomodels.db/BIOMD0000000009) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


