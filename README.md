<p align="center">
<img src="https://github.com/user-attachments/assets/d60e3b4b-5f94-456a-a2dc-39496a7c6c2f", width = "90%" alt="MTDLGAN_workflow>
</p>

MTDL-GAN is a CycleGAN based model that generates multi-target directed ligands (MTDL) from unpaired sets of inhibitor libraries of Alzheimer's disease target enzymes.

#### MTDL-GAN models, structure-based similarity searching and molecular docking simulation results are available for scientific research and drug discovery

Zenodo link: 

The Zip file contains

- data)

ChEMBL27 bioactivity datasets

ChEMBL27 small molecules datasets

Preprocessed original inhibitor (AChE, BACE1, GSK3) molecules

- generated_moldecules)

generated molecular structures from AB, AG, GB MTDL-GAN

XX_topsim_pool_500.csv -> raw data from the model

XX_pool_500.csv -> removing duplicates from the raw data

GBmodel -> saved MTDL models after each epoch

- similiarty_searching

results from structure-based similiarty searching on ChEMBL27 and ExCAPE database

-docking

molecular docking results of the generated MTDLs

Additionally, ExCAPE dataset is available in https://zenodo.org/records/2543724

