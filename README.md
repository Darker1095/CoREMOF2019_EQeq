
These softwares and datebases were required,including **EQeq, Openbabel, CoRE_MOF2019 database**.

The version of Openbabel is *Open Babel 3.1.0*, EQeq software is from https://github.com/numat/EQeq, and CoREMOF2019 files were from **2019-11-01-ASR-public_12020.csv** (https://zenodo.org/record/3677685)

OpenBabel was used to convert data from the CoREMOF2019 database into *CoRE_MOF2019_Openbabel*. An *EQeq_calculated file* was generated for each CIF using the EQeq software. *EQeq_output_cifs* is a collection of all cif files output by EQeq. To make them aesthetically pleasing and user-friendly, we decided to rename all the CIF files within the original COREMOF2019 database. The newly named files correspond to the original CIF names and have the format "rename_*.csv."
