# Multiclass-Multilabel-Classification-Anuran-Calls-MFCCs-Data-Set
Machine Learning project using SVM, SMOTE, K-means clustering to classify Families, Genus, and Species of frogs using Anuran Calls (MFCCs) dataset


Contributor - Shardul Nazirkar

Data Set source - https://archive.ics.uci.edu/ml/datasets/Anuran+Calls+%28MFCCs%29

This dataset was used in several classifications tasks related to the challenge of anuran species recognition through their calls. It is a multilabel dataset with three columns of labels. This dataset was created segmenting 60 audio records belonging to 4 different families, 8 genus, and 10 species. Each audio corresponds to one specimen (an individual frog), the record ID is also included as an extra column. We used the spectral entropy and a binary cluster method to detect audio frames belonging to each syllable. The segmentation and feature extraction were carried out in Matlab. After the segmentation we got 7195 syllables, which became instances for train and test the classifier. These records were collected in situ under real noise conditions (the background sound). Some species are from the campus of Federal University of Amazonas, Manaus, others from Mata AtlÃ¢ntica, Brazil, and one of them from CÃ³rdoba, Argentina. The recordings were stored in wav format with 44.1kHz of sampling frequency and 32bit of resolution, which allows us to analyze signals up to 22kHz. From every extracted syllable 22 MFCCs were calculated by using 44 triangular filters. These coefficients were normalized between -1 â‰¤ mfcc â‰¤ 1.

Each instance has three labels: Families, Genus, and Species. Each of the labels has multiple classes. We wish to solve a multi-class and multi-label problem.

Jupyter notebook is present in the Code directory and the data set is present in the Data directory.

Jupyter Notebook Contents:

1.(a) Loading the Data Set


1.(b) SVM

  i.   Exact match and Hamming loss description
  
  ii.  SVM using Gaaussian kernels and one versus all classifiers
  
  iii. L1-penalized SVM
  
  iv.  SMOTE and L-1 penalized SVM
  
  v.   Checking data imbalance
  


2.    K-Means Clustering with Monte-Carlo Simulation

Skills - Data Science, Machine Learning, SVMs, K-means Clustering

-----------------------------THANK YOU-----------------------------
