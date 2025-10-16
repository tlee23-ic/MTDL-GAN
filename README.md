
<p align="center">
    <img src="https://github.com/user-attachments/assets/d60e3b4b-5f94-456a-a2dc-39496a7c6c2f", width = "90%" alt="MTDLGAN_workflow">
</p>


MTDL-GAN is a CycleGAN based model that generates multi-target directed ligands (MTDLs) from unpaired sets of inhibitor libraries. Our targets of interest are acetylcholinesterase (AChE), beta-secretase 1 (BACE1), and glycogen synthase kinase 3 beta (GSK3), which are known to have significant impacts on the progression and development of AD, each with a different mechanism of action. Inhibitor libraries were curated from ChEMBL27 and further characterized to represent each inhibitor domain, resulting in 69 AChE, 572 BACE1, and 246 GSK3 inhibitors. The MTDL-GAN was trained on these unpaired datasets to generate MTDL-like molecules.

### Code
All codes are available for reproducibility

#### TSNE.ipynb
t-SNE visualisation of reference inhibitors across different stages of domain characterisation method

<p align="center">
    <img width = "90%" alt="TSNE_highres" src="https://github.com/user-attachments/assets/d0932416-bc8c-4826-887d-594f8f637737">
</p>

#### MTDLGAN_GB.ipynb
MTDL-GAN training and molecular structure generation code to generate MTDL-like molecules that inhibit GSK3 and BACE1 enzymes.

<p align="center">
    <img src="https://github.com/user-attachments/assets/c857eb41-b381-41d9-8bfa-6c24df9227a8", width = "90%" alt="MTDLGAN_workflow">
</p>




### Model, Data, Experimental results
MTDL-GAN models, Data, Molecular Docking and Structure-based similarity searching results available at
Zenodo link: https://zenodo.org/records/17206857

The Zip file contains

- data)

ChEMBL27 bioactivity datasets

ChEMBL27 small molecules datasets

Preprocessed original inhibitor (AChE, BACE1, GSK3) molecules

- generated_moldecules)

generated MTDL-like molecular structures from AB, AG, GB MTDL-GAN

XX_topsim_pool_500.csv -> raw data from the model

XX_pool_500.csv -> removing duplicates from the raw data

GBmodel -> saved MTDL models after each epoch

- similiarty_searching

results from structure-based similiarty searching on ChEMBL27 and ExCAPE database

-docking

molecular docking results of the generated MTDLs

Additionally, ExCAPE dataset is available in https://zenodo.org/records/2543724

