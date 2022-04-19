# BioNetworks-Project


Infomap Implmentation Steps:

Dependencies to be installed:
- pip install infomap
- conda install -c conda-forge infomap
- brew install libomp
- pip install umap
- pip install umap-learn
- conda install -c conda-forge umap-learn

Need to clone the partition-validation repo to run solution landscape: git clone https://github.com/mapequation/partition-validation.git 
Now run the command: make -C partition-validation

Steps to run the InfomapGeneration2.ipynh file:
1) download all dependencies above
2) clone the partition validation repo and run the makefile command (in base BioNetworks-Project Folder terminal)
3) run this command: git -C partition-validation pull (in base BioNetworks-Project Folder terminal)
4) run all cells except for the cell containing the function convertData() (this cell modifies the ComNet_all.net file and doesn't need to be modified)
