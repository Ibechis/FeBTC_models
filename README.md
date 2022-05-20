# FeBTC_models

The force_field_validation folder contains the input files used for the validation of the UFF4MOF implementation in LAMMPS and its comparison with GULP and DFT. The DFT fragment was optimised at the B3LYP-D3/6-31G level of theory.

The polymatic_inputs folder provides the lammps data files for the trimer, tetrahedron and BTC linker used as building blocks for Polymatic. These are two sets of inputs, one for the SRO phases and the other for the MIX and MRO phases (they differ in the force field types definition).

The final_models folder contains the five independent amorphous models for the nine systems with at different degree of disorder (SRO, MIX and MRO) and different levels of defects (<10%, 20%, 30 %) related to the following papers:
- [_Nat._ _Commun._ **2021**, _12_, 2062](https://www.nature.com/articles/s41467-021-22218-9) (includes the _SRO <10%_, _MIX <10%_ and _MRO <10%_ phases)
- [_ChemRxiv_ pre-print on modelling defects and disorder in _a_MOFs](https://chemrxiv.org/engage/chemrxiv/article-details/6286b0ed43d1f01722324bdc) (includes all the nine phases)

Files have been renamed to match the nomenclature in the ChemRxiv paper (_'OrderLevel_DefectLevel_ModelNumber'_) and are in extended xyz, pdb and cif format, with pdb and cif including bonding information.  