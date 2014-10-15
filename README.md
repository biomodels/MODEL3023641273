# MODEL3023641273: Ec_iAF1260_flux2

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL3023641273.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL3023641273.git@20140916`


# Model Notes

    
    
    organism        E. coli K-12 MG1655
    model   iAF1260
    Biomass Objective Function (BOF)        Ec_biomass_iAF1260_core_59p81M (E. coli biomass objective function (iAF1260) - core - with 59.81 GAM estimate)
    flux balance analysis objective maximize BOF
    Growth Associated Maintenance (GAM)     59.81 mmol ATP gDW-1
    Non-Growth Associated Maintenance (NGAM)        8.39 mmol ATP gDW-1 hr-1
    media conditions        computational minimal media
    carbon source   11.0 mmol glucose gDw-1 hr-1
    aerobic or anaerobic    18.2 mmol O2 gDw-1 hr-1
    additional constraints
    reactions constrained to zero   152 reactions identified to be unavailable to the cell under glucose aerobic conditions
    flux split between reaction pairs       NDH-1:NDH-2 is 1:1 (3 pairs of reactions - different quinone usage)  NADH10:NADH17pp, NADH5:NADH16pp, NADH9:NADH18p
    p

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
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


