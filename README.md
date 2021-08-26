# Synthetic-Biobots-IGEM-DL-2021
Information about Synthetic Biobots team participating during IGEM Design League 2021. Code and files.

In this repository you can find files and code that was used by Synthetic Biobots with the purpose of developing the IGEM Design League project for 2021. In the descriptions section of this ReadMe file you will find a description of each file in this repository and information such as licencing of the programs used and their usage in the project.


## Descriptions

* [model.pdb](model.pdb): It´s a file that contains the homodimer structure of ArsR protein from E. coli strain K12 substrain MG1655, this structure was predicted by homology modeling using [Swiss-model portal](https://swissmodel.expasy.org/interactive).

* [model1_robetta.pdb](model1_robetta.pdb): A file containing momomer structure of ArsR protein from E. coli strain K12 substrain MG1655, this model was built using [Robetta structure prediction tool](https://robetta.bakerlab.org/submit.php), it was not used any template and the algorithm ussed was RoseTTAFold deep learning based modeling method.

* [alphafold2_model.pdb](alphafold2_model.pdb): This file includes the structure of ArsR protein from E. coli strain K12 substrain MG1655 predicted using [Moonbear server](https://www.getmoonbear.com/AlphaFold2) for ab initio protein structure prediction using AlphaFold2 algorithm.

     *The structure of this three models can be compared using a molecule visualization tool in order to see the high structure similarity between models.*

* [Arsenate.pdb](Arsenate.pdb): Arsenate structure file obtained from [RCSB PDB](https://www3.rcsb.org/ligand/ART) with code ART; it was downloades in SDF format and then converted into PDB using [OpenBabel gui](https://openbabel.org/docs/dev/Installation/install.html).

* [AD4_parameters.dat](AD4_parameters.dat): Parameter file for molecular docking of [ArsR homodimer](model.pdb) and [arsenate](arsenate.pdb) with [Autodock Tools](http://autodock.scripps.edu/resources/adt); this includes the physicochemical properties of arsenic that are necessary for the docking.

* [AD4.1_bound.dat](AD4.1_bound.dat): Parameter file for molecular docking of ArsR homodimer and arsenate with Autodock Tools; this includes the physicochemical properties of arsenic that are necessary for the docking.

* [arsenate_gridparam.gpf](arsenate_gridparam.gpf): Grid parameter file used for docking of ArsR homodimer and arsenate with Autogrid.

* [arsenate_dockparam.dpf](arsenate_dockparam.dpf): Docking parameter file used for docking of ArsR homodimer and arsenate with Autodock.

* [arsenate_docklog.dlg](arsenate_docklog.dlg): Results of molecular docking of ArsR homodimer with arsenate using Autodock; the conformations described in this file can be visualized using Autodock Tools.
