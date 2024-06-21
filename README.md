# Generalizability, robustness, and correction bias of segmentations of thoracic Organs at Risk in CT images

Here is the official repo of the Generalizability, robustness, and correction bias of segmentations of thoracic Organs at Risk in CT images
paper. You will find:
- `fusion.ipynb`: a notebook showing the fusion process of the segmentation masks of the aorta, esophagus, heart and trachea.

Weights of the different models can be obtained at: c.guerendel@nki.nl.

Data from three public datasets are used in this paper:
- The SegTHOR challenge data can be downloaded [here](https://competitions.codalab.org/competitions/21145)
- The Multi-Atlas Labeling Beyond the Cranial Vault - Workshop and Challenge data can be downloaded [here](https://www.synapse.org/Synapse:syn3193805/wiki/217789)
- The OSIC Pulmonary Fibrosis Progression Kaggle challenge data can be downloaded [here](https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression/data?select=train)

Only the training set of the SegTHOR challenge was used to train our models using [nnU-Net V1](https://github.com/MIC-DKFZ/nnUNet/tree/nnunetv1). Their test set is provided on their platform. No public ground truth is given, but online evaluation can be performed their to validate and compare your methods. 

New annotations for the Multi-Atlas Labeling Beyond the Cranial Vault - Workshop and Challenge and the OSIC Pulmonary Fibrosis Progression Kaggle challenge data were necessary to follow the same guidelines as the one of the SegTHOR challenge provided in their [paper](https://arxiv.org/pdf/1912.05950).

For reproducibility of our results on these two datasets, the new annotations made by a board-certified radiologist from the Netherlands Cancer Institute (NKI) can be obtained by requesting from: c.guerendel@nki.nl. Don't hesitate to use them to compare your results with the ones in our paper.
