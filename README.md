# Two-View-Breast-Cancer-Classifier-TPU

This repository contains the notebooks used in Kaggle to develop an undergraduate thesis, and also the models from which the results were extracted. The thesis can be found in https://pcs.usp.br/pcspf/wp-content/uploads/sites/8/2022/12/Monografia_PCS3860_COOP_2022_Grupo_C07.pdf .

The idea was to build a two view classifier for detecting breast cancer capable of running on a TPU based on the architecture created by Petrini et al and described in https://ieeexplore.ieee.org/document/9837037.

The dataset used is Curated Breast Image Subset
of Digital Database for Screening Mammography (CBIS-DDSM), in particular, a version form Owsef and available in Kaggle through the link https://www.kaggle.com/datasets/awsaf49/cbis-ddsm-breast-cancer-image-dataset, from which versions using TFRecords format were created for the different components created, and are all available in Kaggle.

Patches 224x224 - https://www.kaggle.com/dsv/4400757
Patches 448x448 - https://www.kaggle.com/dsv/4465927
One View Mammograms - https://www.kaggle.com/dsv/4429171
Two View Mammograms - https://www.kaggle.com/dsv/4433185

The notebooks with each component are in the 'notebooks' folder and the models used in the thesis are available in the following Kaggle dataset:

Models: - https://www.kaggle.com/dsv/4746020
