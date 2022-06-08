# sarcasm-detection
"Sarcasm Detection in Amazon Customer Reviews using Common Sense" - Thesis for Master's Degree in Machine Learning

This repositorcontains the code source required to replicate the results presented in the above thesis.

The entire code for this study is written in the python programming language. The details of the other tools and libraries used for this study are provided in section 4.6 of the code. required citations and references are provided in the theis report. The code implementation and the model building primarily comprise the below major checkpoints or milestones.  

i.	Dataset Selection
ii.	Data Preparation
iii.	Baseline Model
iv.	Common Sense Infused Model
v.	GCN based model

The python notebooks can be run directly from jupyter, in the sequence given below. Recommend using Google Colab with PyTorch.

1. prepare-dataset.ipynb - This notebook covers the Data selection and prepration
2. baseline-plm.ipynb - This notebook covers the baseline model using any of the pre-trained language model. Hyperparameters and choice of the PLM can be varied using the variables provided.
3. comet-plm.ipynb - This notebook covers the usage of COMET model along with any of the pre-trained language model. Hyperparameters and choice of the PLM can be varied using the variables provided.
4. gcn-comet-plm - This notebook covers the GCN model on top of the COMET+PLM model. Hyperparameters and choice of the PLM can be varied using the variables provided.
