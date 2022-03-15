# -CHEM101.6
For course CHEM101.6 in Dartmouth


Final project folder contains notebook and files needed to complete an Autodock attempt for disordered protein AR_Tau5 and p53 with small molecule ligands.


In AR_protein folder contains 9 frames of pdb and pdbqt from a long time simulation, and in pdbqt folder is the pdbqt for ligand EPI-7170 (for AR system) and EGCG (for p53 system).

protein.pdbqt and ligand.pdbqt serves as an example for the first part of autodock vina test, to run docking on the whole protein.

conf.txt is also an example of the file format needed for vina input.


In the final project notebook, three parts of autodock attempt are shown:
  1. Use autodock vina python package to perform docking on the whole protein of p53.
  2. Use autodock vina python package to perform docking on the whole protein of AR_Tau5 for 9 frames of pdbs.
  3. Use command line vina to perform docking on each residue of AR_Tau5 for 9 frames of pdbs, and rank the binding affinity for each residue.


**Installation:**

**To get vina working in command line:**

Download autodock_vina_1_1_2_linux_x86.tgz from here: https://vina.scripps.edu/downloads/

tar xzvf autodock_vina_1_1_2_linux_x86.tgz

alias vina /content/autodock_vina_1_1_2_linux_x86/bin/vina


**To install vina with a python package:**

conda install -c bioconda autodock-vina
