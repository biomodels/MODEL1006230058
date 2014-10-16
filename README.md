# MODEL1006230058: Matsuoka2003_VentricularCells_SinoatrialNodePacemaker

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230058.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230058.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230058 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Role of individual ionic current systems in ventricular cells hypothesized by a model study.**   
Matsuoka S, Sarai N, Kuratomi S, Ono K, Noma A. _Jpn J Physiol_ 2003
Apr;53(2):105-23 [12877767](http://www.ncbi.nlm.nih.gov/pubmed/12877767) ,  
**Abstract:**   
Individual ion channels or exchangers are described with a common set of
equations for both the sinoatrial node pacemaker and ventricular cells. New
experimental data are included, such as the new kinetics of the inward
rectifier K+ channel, delayed rectifier K+ channel, and sustained inward
current. The gating model of Shirokov et al. (J Gen Physiol 102: 1005-1030,
1993) is used for both the fast Na+ and L-type Ca2+ channels. When combined
with a contraction model (Negroni and Lascano: J Mol Cell Cardiol 28: 915-929,
1996), the experimental staircase phenomenon of contraction is reconstructed.
The modulation of the action potential by varying the external Ca2+ and K+
concentrations is well simulated. The conductance of I(CaL) dominates membrane
conductance during the action potential so that an artificial increase of
I(to), I(Kr), I(Ks), or I(KATP) magnifies I(CaL) amplitude. Repolarizing
current is provided sequentially by I(Ks), I(Kr), and I(K1). Depression of ATP
production results in the shortening of action potential through the
activation of I(KATP). The ratio of Ca2+ released from SR over Ca2+ entering
via I(CaL) (Ca2+ gain = approximately 15) in excitation-contraction coupling
well agrees with the experimental data. The model serves as a predictive tool
in generating testable hypotheses.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Matsuoka S, Sarai N, Kuratomi S, Ono K, Noma A.
(2003) - version=1.0**
](http://models.cellml.org/exposure/372e22e528b72f9efc9c33954ada281c)  
The original CellML model was created by:  
**Penny Noble**   
penny.noble@dpag.ox.ac.uk  
The University of Oxford  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not. .  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


