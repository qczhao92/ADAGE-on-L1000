# Human ADAGE Model (HAM)
Implement Analysis using Denoising Autoencoder of Gene Expression (ADAGE) in L1000 Connectivity Map perturbational profile dataset.
This is a group project for course AI in Genomics 2021 (District3, Mila, Montreal Univiversity, Concordia University, Montreal, QC, CANADA). 

======================================
Group members: Yu Zhan, Qingchuan Zhao

Mentor: Paul Bertin

======================================

# Objectives:
Develop an machine learning algorithm to characterize differential gene expression in cancer cell lines treated by drugs.


# References:
Original ADAGE model is published in Tan et al. NSBT (2015) and Tan et al. BMC Bioinformatics (2017)

L1000 data set we used in is from:
Subramanian A. et al. "A Next Generation Connectivity Map: L1000 Platform and the First 1,000,000 Profiles." Cell 171(6): 1437-1452 e1417.


# Explanations of use notebook

We focused only on 978 landmark genes in data set.

ADAGE Project Model implementation.ipynb tested ADAGE with linear encoder and multilayer decoders.

rADAGE.ipynb tested similar model with linear decoder and multilayers encoders.

DNA damage repair pathway inhibitors ADAGE/rADAGE.ipynb utilized a subset of samples including ten selected drugs:
olaparib, rucaparib, talazoparib, veliparib, iniparib, lomeguatrib, mitoxantrone, AZD-7762, camptothecin, irinotecan


