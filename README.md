# MOBI2.1_local
This repository contains run directories for MOBI2.1 with different configurations.

mobi_o2_n_fe_si_ca_caco3_c13_n15_c14 includes oxygen, nitrogen, iron, silicon, carbon/alkalinity, calcium carbonate, and the isotopes 13C, 15N and radiocarbon. This directory includes variable P:N and Si:N stoichiometry contributed by Nate Fillmann.

mobi_o2_n_fe_si_ca_caco3_c14 includes all of the above prognostic variables except 13C and 15N. This version is considerably faster than the one with those isotopes. This directory does not include variable stoichiometry.

More configurations will be added shortly

More info about different configurations in the previous version (MOBI2.0) is available [here](https://github.com/andreasschmittner/UVic2.9/wiki/Model-of-Ocean-Biogeochemistry-and-Isotopes-(MOBI)).  
Note that some of the options have changed (e.g. O_npzd is now O_mobi). This document will be updated shortly.
## Getting Started
To run a version you need to copy the data directory into the run directory.
You will also need to change the path to the base code at the top of the mk.in file.

