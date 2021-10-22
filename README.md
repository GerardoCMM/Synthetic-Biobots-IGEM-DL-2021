# Synthetic-Biobots-IGEM-DL-2021
Information about Synthetic Biobots team participating during IGEM Design League 2021. Code and files.

In this repository you can find files and code that was used by Synthetic Biobots with the purpose of developing the IGEM Design League project for 2021. In the descriptions section of this ReadMe file you will find a description of each file in this repository and information such as licencing of the programs used and their usage in the project.


## Descriptions
* [AD4.1_bound.dat](AD4.1_bound.dat): Parameter file for molecular docking of ArsR homodimer and arsenate with Autodock Tools; this includes the physicochemical properties of arsenic that are necessary for the docking.

* [AD4_parameters.dat](AD4_parameters.dat): Parameter file for molecular docking of [ArsR homodimer](model.pdb) and [arsenate](arsenate.pdb) with [Autodock Tools](http://autodock.scripps.edu/resources/adt); this includes the physicochemical properties of arsenic that are necessary for the docking.

* [Arsenate.pdb](Arsenate.pdb): Arsenate structure file obtained from [RCSB PDB](https://www3.rcsb.org/ligand/ART) with code ART; it was downloades in SDF format and then converted into PDB using [OpenBabel gui](https://openbabel.org/docs/dev/Installation/install.html).

* [BBa_J61100](BBa_J61100.fasta): RBS (Ribosome Binding Site) from [iGEM Part:BBa_J61100](http://parts.igem.org/Part:BBa_J61100). Designed by: John Anderson Group: Arkin Lab (2007-01-28)

* [IDLBB_002051](IDLBB_002051.fasta): Arsenic Biosensor Transcriptional Unit. Made of ABS (ArsR Binding Site) 23-56, PArsR (Promoter) 49-85, RBS (Ribosome Binding Site) 94-107, ArsR (CDS) 114-467, ABS (ArsR Binding Site) 476-509, RBS (Ribosome Binding Site) 518-531, GFP (CDS) 538-1257 and rrnBT1 (Terminator) 1266-1345.

* [IDLBB_002052](IDLBB_002052.fasta): Cadmium Biosensor Transcriptional Unit. Made of Reverse rrnBT1 (Terminator) 23-102, Reverse CadR (CDS) 111-554, Reverse RBS (Ribosome Binding Site) 561-574, Reverse Bidirectional Promoter 583-666, RBS (Ribosome Binding Site) 675-688, mCherry (CDS) 695-140 and rrnBT1 (Terminator) 1414-1493.

* [IDLBB_002053](IDLBB_002053.fasta): Cadmium and Arsenic Remediaton Transcriptional Unit. Made of pL (Promoter) 23-266, RBS (Ribosome Binding Site) 275-288, ArsB (CDS) 295-1584, RBS (Ribosome Binding Site) 1593-1606, ArsC (CDS) 1613-2038, RBS (Ribosome Binding Site) 2047-2060, CadA (CDS) 2067-4280 and rrnBT1 (Terminator) 4289-4368.

* [IDLBB_002054](IDLBB_002054.fasta): Temperature Sensitive Lambda cI Repressor Transcriptional Unit. Made of p(Bla) (Promoter) 23-57, RBS (Ribosome Binding Site) 66-79, cI875 (CDS) 86,799 and rrnBT1 (Terminator) 808-887.

* [IDLBB_002056](IDLBB_002056.fasta): ABS (ArsR Binding Site), as in [Xu, C. (1996)](https://doi.org/10.1074/jbc.271.5.2427).

* [IDLBB_002057](IDLBB_002057.fasta): PArsR (ArsR Promoter), as in [Xu, C. (1996)](https://doi.org/10.1074/jbc.271.5.2427).

* [alphafold2_model.pdb](alphafold2_model.pdb): This file includes the structure of ArsR protein from E. coli strain K12 substrain MG1655 predicted using [Moonbear server](https://www.getmoonbear.com/AlphaFold2) for ab initio protein structure prediction using AlphaFold2 algorithm.





