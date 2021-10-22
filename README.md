# Synthetic-Biobots-IGEM-DL-2021
Information about Synthetic Biobots team participating during IGEM Design League 2021.

In this repository you can find files and parts that were used by Synthetic Biobots with the purpose of developing the IGEM Design League project for 2021. In the descriptions section of this ReadMe file you will find a description of each file in this repository and aditional information.


## Descriptions
* [AD4.1_bound.dat](AD4.1_bound.dat): Parameter file for molecular docking of ArsR homodimer and arsenate with Autodock Tools; this includes the physicochemical properties of arsenic that are necessary for the docking.

* [AD4_parameters.dat](AD4_parameters.dat): Parameter file for molecular docking of [ArsR homodimer](model.pdb) and [arsenate](arsenate.pdb) with [Autodock Tools](http://autodock.scripps.edu/resources/adt); this includes the physicochemical properties of arsenic that are necessary for the docking.

* [Arsenate.pdb](Arsenate.pdb): Arsenate structure file obtained from [RCSB PDB](https://www3.rcsb.org/ligand/ART) with code ART; it was downloades in SDF format and then converted into PDB using [OpenBabel gui](https://openbabel.org/docs/dev/Installation/install.html).

* [BBa_B0010](BBa_B0010.fasta): rrnBT1 (Terminator) from [iGEM Part:BBa_B0010](http://parts.igem.org/Part:BBa_B0010). Designed by: Randy Rettberg Group: Antiquity (2003-11-19).

* [BBa_I14018](BBa_I14018.fasta): p(Bla) (Constitutive promoter), E. coli sigma70, from [iGEM Part:BBa_I14018](http://parts.igem.org/Part:BBa_I14018). Designed by: Vikram Vijayan, Allen Hsu, Lawrence Fomundam Group: Antiquity (2004-08-02).

* [BBa_J61100](BBa_J61100.fasta): RBS (Ribosome Binding Site) from [iGEM Part:BBa_J61100](http://parts.igem.org/Part:BBa_J61100). Designed by: John Anderson Group: Arkin Lab (2007-01-28).

+ [BBa_K200016](BBa_K200016.fasta): Temperature Sensitive Lambda cI Repressor, with cI857 mutation, from [iGEM Part:BBa_K200016](http://parts.igem.org/Part:BBa_K200016). Designed by: Royah Vaezi Group: iGEM09_Imperial College London (2009-10-14). 

* [BBa_K2282004](BBa_K2282004.fasta): pL (Promoter), from [iGEM Part:BBa_K2282004](http://parts.igem.org/Part:BBa_K2282004). Designed by: Eliott LAFON Group: iGEM17_IONIS-PARIS (2017-10-02). The promoter is repressed at low temperature by cI857 protein, this protein loses repression activity when temperature rises from 30°C until 42°C.

* [IDLBB_002051](IDLBB_002051.fasta): Arsenic Biosensor Transcriptional Unit. Made of ABS (ArsR Binding Site) 23-56, PArsR (Promoter) 49-85, RBS (Ribosome Binding Site) 94-107, ArsR (CDS) 114-467, ABS (ArsR Binding Site) 476-509, RBS (Ribosome Binding Site) 518-531, GFP (CDS) 538-1257 and rrnBT1 (Terminator) 1266-1345.

* [IDLBB_002052](IDLBB_002052.fasta): Cadmium Biosensor Transcriptional Unit. Made of Reverse rrnBT1 (Terminator) 23-102, Reverse CadR (CDS) 111-554, Reverse RBS (Ribosome Binding Site) 561-574, Reverse Bidirectional Promoter 583-666, RBS (Ribosome Binding Site) 675-688, mCherry (CDS) 695-140 and rrnBT1 (Terminator) 1414-1493.

* [IDLBB_002053](IDLBB_002053.fasta): Cadmium and Arsenic Remediaton Transcriptional Unit. Made of pL (Promoter) 23-266, RBS (Ribosome Binding Site) 275-288, ArsB (CDS) 295-1584, RBS (Ribosome Binding Site) 1593-1606, ArsC (CDS) 1613-2038, RBS (Ribosome Binding Site) 2047-2060, CadA (CDS) 2067-4280 and rrnBT1 (Terminator) 4289-4368.

* [IDLBB_002054](IDLBB_002054.fasta): Temperature Sensitive Lambda cI Repressor Transcriptional Unit. Made of p(Bla) (Promoter) 23-57, RBS (Ribosome Binding Site) 66-79, cI875 (CDS) 86,799 and rrnBT1 (Terminator) 808-887.

* [IDLBB_002056](IDLBB_002056.fasta): ABS (ArsR Binding Site), as in [Xu, C. (1996)](https://doi.org/10.1074/jbc.271.5.2427).

* [IDLBB_002057](IDLBB_002057.fasta): PArsR (ArsR Promoter), as in [Xu, C. (1996)](https://doi.org/10.1074/jbc.271.5.2427).

* [IDLBB_002058](IDLBB_002058.fasta): ArsR (CDS), Metalloregulatory Protein from Escherichia coli str. K-12 substr. MG1655, complete genome [U00096.3](https://www.ncbi.nlm.nih.gov/nuccore/U00096.3/) (3648528..3648881). In absence of arsenate represses transcription by binding [ABS](IDLBB_002056.fasta), in its presence it allows transcription.

* [IDLBB_002059](IDLBB_002059.fasta): GFP (CDS) Green Fluorescent Protein.

* [IDLBB_002060](IDLBB_002060.fasta): CadR (CDS), Regulatory protein from Pseudomonas putida, complete genome [CP007620.1](https://www.ncbi.nlm.nih.gov/nuccore/CP007620.1/) (5933128..5933571). In absence of cadmium it binds [PCadR/CadA](IDLBB_002061.fasta) and represses CadA transcription, in its presence it allows and favors transcription.

* [IDLBB_002061](IDLBB_002061.fasta): PCadR/CadA (Bidirectional promoter), from Pseudomonas putida, complete genome [CP007620.1](https://www.ncbi.nlm.nih.gov/nuccore/CP007620.1/) (5933044..5933127).

* [IDLBB_002062](IDLBB_002062.fasta): mCherry (CDS), Fluorescent protein, with a synonymal puntual mutation (357), G to A, in order to achieve standarization [RFC[10]](https://parts.igem.org/Help:Standards/Assembly/RFC10).

* [IDLBB_002063](IDLBB_002063.fasta): ArsB (CDS), arsenite/antimonite:H(+) antiporter from Escherichia coli str. K-12 substr. MG1655, complete genome [U00096.3](https://www.ncbi.nlm.nih.gov/nuccore/U00096.3/) (3648935..3650224).

* [IDLBB_002064](IDLBB_002064.fasta): ArsC (CDS), Arsenate Reductase from Escherichia coli str. K-12 substr. MG1655, complete genome [U00096.3](https://www.ncbi.nlm.nih.gov/nuccore/U00096.3/) (3650237..3650662)

* [IDLBB_002065](IDLBB_002065.fasta): CadA (CDS), Cadmium transporting ATPase from Pseudomonas putida, Regulatory protein from Pseudomonas putida, complete genome [CP007620.1](https://www.ncbi.nlm.nih.gov/nuccore/CP007620.1/) Complement(5930830..5933043), synonymal puntual mutation (213), A to G, in order to achieve standarization [RFC[10]](https://parts.igem.org/Help:Standards/Assembly/RFC10).

* [alphafold2_model.pdb](alphafold2_model.pdb): This file includes the structure of ArsR protein from E. coli strain K12 substrain MG1655 predicted using [Moonbear server](https://www.getmoonbear.com/AlphaFold2) for ab initio protein structure prediction using AlphaFold2 algorithm.





