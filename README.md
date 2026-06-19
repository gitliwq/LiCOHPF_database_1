# LiCOHPF_database_1
This repository includes training data, test data and the input for training using MTP or mace. 
If you use data, please cite this paper: 
-Li, W. Q., Wu, G., Arce-Ramos, J. M., Lau, Y. H., & Ng, M. F. (2025). Enabling accurate modelling of materials for a solid electrolyte interphase in lithium-ion batteries using effective machine learning interatomic potentials. Materials Horizons, 12(24), 10770-10781.DOI: 10.1039/D5MH01343G

## MTP
- pot.tar.gz # obtained MTP model
- MTP_d3_16_520.tar.gz  # training data from DFT+d3
- train-output-d3.txt #parameters for MTP training and output

## mace
- MACE_model.tar.gz  # obtained model
- mace_train.sh  #parameters for mace
- MTP_d3_16_520.tar.gz #training data from DFT+d3

## test_sets
- tar -zxvf xxx.tar.gz
- Each file include 10000 structures
