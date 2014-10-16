# BIOMD0000000436: BIOMD0000000436

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000436.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000436.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000436 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Gupta2009 - Eicosanoid Metabolism

Integrated model of eicosanoid metabolism and signaling based on lipidomics
flux analysis.

This model is described in the article:

[An integrated model of eicosanoid metabolism and signaling based on
lipidomics flux analysis.](http://identifiers.org/pubmed/19486676)

Gupta S, Maurya MR, Stephens DL, Dennis EA, Subramaniam S.

Biophys. J. 2009 Jun; 96(11):4542-51.

Abstract:

There is increasing evidence for a major and critical involvement of lipids in
signal transduction and cellular trafficking, and this has motivated large-
scale studies on lipid pathways. The Lipid Metabolites and Pathways Strategy
consortium is actively investigating lipid metabolism in mammalian cells and
has made available time-course data on various lipids in response to treatment
with KDO(2)-lipid A (a lipopolysaccharide analog) of macrophage RAW 264.7
cells. The lipids known as eicosanoids play an important role in inflammation.
We have reconstructed an integrated network of eicosanoid metabolism and
signaling based on the KEGG pathway database and the literature and have
developed a kinetic model. A matrix-based approach was used to estimate the
rate constants from experimental data and these were further refined using
generalized constrained nonlinear optimization. The resulting model fits the
experimental data well for all species, and simulated enzyme activities were
similar to their literature values. The quantitative model for eicosanoid
metabolism that we have developed can be used to design experimental studies
utilizing genetic and pharmacological perturbations to probe fluxes in lipid
pathways.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000436](http://identifiers.org/biomodels.db/BIOMD0000000436) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


