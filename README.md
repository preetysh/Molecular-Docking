# Protein Modeling & Drug Docking (SARS-CoV 2):
<sup> The molecular docking method is used to simulate the atomic-level interaction between a small molecule and a protein, allowing us to define how small molecules behave in the binding site of our target proteins and to better understand basic biological processes. The docking procedure involves two fundamental steps: estimation of the binding affinity and prediction of the ligand structure, as well as its location and orientation inside these sites (often referred to as pose).</sup> <sup> The steps that come after designing or discovering a novel medicine are expensive and time-consuming. Drug development can take anywhere between 12 and 15 years and cost billions of dollars. In silico molecular docking studies have been found to speed up the discovery rate and decrease the need for costly lab labour. Therefore, molecular docking studies are essential for accelerating drug discovery and screening procedures, especially in situations like the current COVID-19 epidemic.

<sup> Here, a 3D structure of a SARS-CoV-2 protein sequence is constructed using Homology modeling and execute Molecular docking of the medicines against the protein molecule and deduce the protein- drug interaction, which is crucial in the drug development and screening process. Structural databases such as Protein Data Bank (PDB) as well online protein visualization and analysis tools such as  SWISS-MODEL, PyMOL, AutoDock Vina etc are used in this project. <sup/> 

<sup> Receptor protein used here is 2ghv spike protein of Corona virus, whereas ligand or the drug used here is Chloroquine.<sup/>

### Swiss-Model:

<sup> Accessible through the Expasy web server or the software DeepView, SWISS-MODEL is a fully automated protein structure homology-modeling platform (Swiss Pdb-Viewer). All life science researchers across the world can use this site to access protein modelling. We can access the website here : [Swiss-Model]( https://swissmodel.expasy.org/). We can build the model of the required protein by uploading the target sequence file (Fasta sequence) through this. <sup/>

### Protein Data Bank (PDB):

<sup> We can also get the protein structure from PDB which is a database for the three-dimensional structural information of large biological molecules like proteins and nucleic acids. We can access the website here: [RCSB PDB](https://www.rcsb.org/) <sup/>

#### Structure of the 2ghv spike protein:
<sup> ![2ghv](https://github.com/preetysh/Molecular-Docking/blob/a3f090fd0e4fc9ed13873820194f98eb372473c7/2GHV.png) 

### PubChem Database:
<sup> PubChem is the world's largest collection of freely accessible chemical information. The drug used in this project for docking with the protein is taken from this database. The drug selected for docking with 2ghv spike protein is Chloroquine.

#### Chloroquine
<sup> Chloroquine is indicated to treat infections of _P. vivax_, _P. malariae_, _P. ovale_, and susceptible strains of _P. falciparum_. It is also used to treat extraintestinal amebiasis. Chloroquine is also used off label for the treatment of rheumatic diseases, as well as treatment and prophylaxis of Zika virus. Chloroquine is currently undergoing clinical trials for the treatment of COVID-19.

#### Structure of Chloroquine:
<sup> ![Chloroquine](https://github.com/preetysh/Molecular-Docking/blob/36ab48d1eba831fc90968d1fe7486dc0ef31c6be/Chloroquine_100.png)
  
<sup> Homology modelling has emerged as a useful tool for the prediction of protein structures. The idea behind homology modelling, also known as comparative modelling, is that two homologous sequences produce protein structures that are comparable to one another. By using a homologous protein's template structure and sequence as building blocks, homology modelling creates an atomic-resolution model of the targeted protein. The quality of a homology model is determined by the template's quality and the degree of sequence similarity between the target protein and the template.
 
### PyMol:

<sup> PyMOL is a free and open-source molecular visualisation tool developed by Warren Lyford DeLano and sold at first by DeLano Scientific LLC.

#### Computer-Aided Drug Design (CADD)
<sup> CADD involves small molecular preparation (such as generating the three-dimensional (3D) structure from a two-dimensional (2D) scheme, ligand conformation search, and energy minimization), homology modelling, protein preparation (such as pKa calculation, Asn, Gln, and His sidechain flipping, H-bond network optimization, and energy minimization), lead design (such as docking, design in situ, pharmacophore modelling, and VS), and molecular dynamics (MS).

#### Visualization:
<sup> PyMOL has become one of the best known programmes for creating high-resolution pictures of macromolecules for publications, due to its extensive use in 3D visualisation of macromolecules.
  
#### Macromolecule Editing:
<sup> PyMOL has the ability to modify a macromolecule, including altering the dihedral angles, building a peptide, replacing a residue, and more. With PyMOL's Builder toolkit, one can also quickly create a molecule from nothing. 

#### Protein Preparation:
<sup> Numerous defects may be detected in crystal structures and homology models, such as the incorrect conformation of Asn, Gln, and His, atom crashes, and the absence of pKa data. Therefore, protein preparation is a necessary step before performing any other molecular modelling work in order to acquire precise and trustworthy computational findings. This involves modifying the conformation/protonation state of the residues Asn, Gln, and His; fine-tuning the H-bond network; and energy minimization.
  
#### Ligand Preparation:
<sup> Prior to doing any additional modelling activities in structure-based protein-ligand modelling, all ligands must be properly prepared with the correct 3D geometries, suitable bond ordering, accessible tautomer, and proper ionisation states.
  
  
### Protein–Ligand Docking

<sup> The aim of protein–ligand docking is to predict the location and orientation of a ligand in the binding pocket of a particular receptor.
  
#### Autodock/VINA:
<sup> AutoDock is a suite of automated docking tools. With the help of the Autodock/Vina plugin, users can define binding sites, export them to Autodock and VINA input files, automatically prepare receptors and ligands, run Autodock or VINA docking, view grid maps produced by autogrid in PyMOL, handle multiple ligands, and set up flexible sidechain docking, among other tasks. Current distributions of AutoDock consist of two generations of software: AutoDock 4 and AutoDock Vina. AutoDock Vina does not require choosing atom types and pre-calculating grid maps for them. Instead, it calculates the grids internally, for the atom types that are needed, and it does this virtually instantly.

##### Autodock Screenshot:
![Autodock](https://github.com/preetysh/Molecular-Docking/blob/98733d6a1c5a3ded64dc2c249228a91a0add127a/Autodock.jpg)
###### (Forli,S et.al; 2016)
  
  
  
  
  
  
  
  
  
  
  
  
  
#### References:
  
##### 1. Yuan, S., Chan, H. S., & Hu, Z. (2017). Using PyMOL as a platform for computational drug design. Wiley Interdisciplinary Reviews: Computational Molecular Science, 7(2), e1298.
##### 2. Robinson, S. W., Afzal, A. M., & Leader, D. P. (2014). Bioinformatics: Concepts, methods, and data. Handbook of Pharmacogenomics and stratified medicine, 259-287.
##### 3. Forli, S., Huey, R., Pique, M. et al. Computational protein–ligand docking and virtual drug screening with the AutoDock suite. Nat Protoc 11, 905–919 (2016).
##### 4. PubChem
