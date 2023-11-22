# Previous Requirements

This directory contains all the necessary files and requirements needed to set up and execute the energy analysis of protein-protein interactions. Below is a list of files and their descriptions, along with the installation instructions.

## Files and Descriptions

- `6m0j.cif` - The Crystallographic Information File (CIF) containing the 3D structure of the protein of interest.
- `6m0j.pdb` - The Protein Data Bank (PDB) file with the 3D coordinates of the protein structure.
- `6m0j_fixed.pdb` - A PDB file with corrected coordinates and possibly optimized for better computational analysis.
- `residue_library.txt` - A text file containing a library of raw residue data used in the energy calculations.
- `vdwprm` - A file containing parameters for van der Waals forces used in the energy analysis.

## Installation

Before starting the energy analysis, ensure that all necessary software and libraries are installed. The following requirements must be met:

- **PyMOL**: For the visualization and analysis of protein structures. Install PyMOL from [their website](https://pymol.org).
- **Python**: Ensure that Python is installed and properly configured. The analysis scripts are compatible with Python 3.x.
- **Biopython**: This library is essential for parsing PDB files and performing computational tasks. Install it using `pip install biopython`.
- **NACCESS**: The NACCESS tool is used for accessible surface area calculations.
- **Matplotlib**: For plotting and visualization of results. Install it using `pip install matplotlib`.
