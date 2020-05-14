Set of 42 protein-ligand complexes
==================================

# Overview

The ligands herein vary in the number of atoms and number of rotatable bonds.
Furthermore, most of these protein-ligand complexes were chosen because they
were particularly sensitive to the performance of different search algorithms.

This is a subset of the data used in the following study:
Accelerating AutoDock4 with GPUs and Gradient-Based Local Search
https://dx.doi.org/10.26434/chemrxiv.9702389.v1

# Warning

These structures, both proteins and ligands, were prepared in an automated way
without manual inspection. The following is a non-comprehensive list of
issues that may exist:

* missing water molecules that bridge ligand-receptor interactions,
* missing atoms in the proteins,
* non-integer sum of partial charges,
* incorrect protonation state,
* incorrect protein conformations.

This intended use of this data is to evaluate the performance of docking with
regard to computational and algorithmic efficiency, but not the accuracy of
the scoring function.

# Number of atoms and rotatable bonds 

<img src="atoms_vs_rotbonds.png" width="700">


# Details

In ligand\_properties.csv
* `pdb` Protein Data Bank accession code
* `n_atom` number of atoms in the ligand
* `n_tors` number of bonds in the ligand that can rotate during docking
* `score_of_probable_global_minimum` best score that can be calculated with probable convergence (score is the sum of intra- and inter-moleculer energy components) 
* `RMSD_of_probable_global_minimum` RMSD from X-ray pose for the solution with the best score 
