# VASP Scripts
Various Python and bash scripts for pre- and post-processing of VASP calculations.

## xdatcar2xyz.py
Converts an XDATCAR file to an xyz file, accounting for changes in the lattice vectors (e.g., ISIF=3).

## get_md_data.sh
Extracts energy, pressure and temperature data for an NPT MD simulation.

## plot.py
Plots one of the variables from get_md_data.sh.

## orbital_pdos.py
Extracts the orbital-projected pdos from the DOSCAR file (LORBIT = 11). Requires input file called "projection" - see example. 
