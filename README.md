# Shell-Optimized Atomic Confinement (SOAC) '.skf' Files

This repository contains Slater-Koster files developed by the [Voss group](https://vossgroup.sites.stanford.edu/) for the electronic structure calculations of transition metals, ranging from Scandium (Sc) to Gold (Au). These files are specifically optimized for use with the **DFTB+** code.

In addition to the `.skf` files, the repository includes Python dictionaries containing atomic spin constants. These constants have been derived from free atomic calculations and optimized for bulk material simulations.

The parameters are provided for the following exchange-correlation functionals:
- GGA-PBE
- GGA-PBEsol
- GGA-rPBE
- LDA

# How to Use

To use these Slater-Koster files with **DFTB+**, ensure that the path to the `.skf` files is correctly specified in your input files. Atomic spin constants can additionaly be used through the SpinConstants **DFTB+** key-word in spin-polarized calculations. 

# Referenced Work

When utilizing the files in this repository, please refer to them collectively as "SOAC" parameters. The SOAC method was developed in the following study, which should be cited in any related publications:

F. Balzaretti and J. Voss, *J. Chem. Theory Comput.*, 2024. [DOI](https://doi.org/10.1021/acs.jctc.4c00345)
