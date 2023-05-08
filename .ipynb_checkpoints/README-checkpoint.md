# CancerBioInformatics

## Motivation
Prostate cancer is a major cause of cancer-related mortality, particularly among men. Advanced genetic analysis using machine learning has the potential to identify individuals who are at a higher risk of developing metastatic prostate cancer. We aimed to find and validate a set of genes that predicted whether prostate cancer metastasis to adjacent lymph nodes using machine learning and statistical methods including K-means clustering, neural network, Naïve Bayesian classifications and PCA.
This project was inspired by Elham Shamsara and Jamal Shamsara's paper Bioinformatics analysis of the genes involved in the extension of prostate cancer to adjacent lymph nodes by supervised and unsupervised machine learning methods: The role of SPAG1 and PLEKHF2. (https://pubmed.ncbi.nlm.nih.gov/32619574/)

## Datasets
The dataset was downloaded directly from the Shamsara paper (https://data.mendeley.com/datasets/fdb8f5hjyd/1). According to the paper, this is a TCGA dataset of Prostate Adenocarcinoma containing the mRNA expression data of 20471 genes from 417 patients with prostate cancer that either spread to adjacent lymph nodes (N1) or remained local type (N0). 

## Organization
This projects contained three folders including initial data processing and analysis, supervised machine learning, and unsuparvised machine learning. It is necessary to go through data processing and obtain the correct data format (introduced in Data Processing) before proceeding to other folders. The order of supervised learning and unsupervised learning does not affect each other. However, it is more recommended to go through unsupervised learning as it requires less ML background.

## Acknowledgment
This project is an independent study (CSC391) on Cancer Classification with Machine Learning lead by Jingyun Qian, under the guidance of Dr. Michelle P. Kuchera, and Dr. Laurie Heyer.

All of the data analyses were performed using Scikit-learn and Keras.

## Reference
1. Shamsara, E., & Shamsara, J. (2020). Bioinformatics analysis of the genes involved in the extension of prostate cancer to adjacent lymph nodes by supervised and unsupervised machine learning methods: The role of SPAG1 and PLEKHF2. Genomics, 112(6), 3871–3882. https://doi.org/10.1016/j.ygeno.2020.06.035
2. `scikit-learn`: Pedregosa, F., Varoquaux, G., Gramfort, A., Michel, V., Thirion, B., Grisel, O., ... & Vanderplas, J. (2011). Scikit-learn: Machine learning in Python. Journal of machine learning research, 12(Oct), 2825-2830. https://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html
3. `Keras`: Chollet, F. (2015). Keras. https://keras.io/