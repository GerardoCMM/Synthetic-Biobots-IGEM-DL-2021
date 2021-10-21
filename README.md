# Synthetic-Biobots-IGEM-DL-2021
Information about Synthetic Biobots team participating during IGEM Design League 2021. Code and files.

In this repository you can find files and code that was used by Synthetic Biobots with the purpose of developing the IGEM Design League project for 2021. In the descriptions section of this ReadMe file you will find a description of each file in this repository and information such as licencing of the programs used and their usage in the project.


## Descriptions

* [alphafold2_model.pdb](alphafold2_model.pdb): This file includes the structure of ArsR protein from E. coli strain K12 substrain MG1655 predicted using [Moonbear server](https://www.getmoonbear.com/AlphaFold2) for ab initio protein structure prediction using AlphaFold2 algorithm.

* [Arsenate.pdb](Arsenate.pdb): Arsenate structure file obtained from [RCSB PDB](https://www3.rcsb.org/ligand/ART) with code ART; it was downloades in SDF format and then converted into PDB using [OpenBabel gui](https://openbabel.org/docs/dev/Installation/install.html).

* [AD4_parameters.dat](AD4_parameters.dat): Parameter file for molecular docking of [ArsR homodimer](model.pdb) and [arsenate](arsenate.pdb) with [Autodock Tools](http://autodock.scripps.edu/resources/adt); this includes the physicochemical properties of arsenic that are necessary for the docking.

* [AD4.1_bound.dat](AD4.1_bound.dat): Parameter file for molecular docking of ArsR homodimer and arsenate with Autodock Tools; this includes the physicochemical properties of arsenic that are necessary for the docking.

