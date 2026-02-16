# Project 1 DS4002 Group 10

## Contents

1: This repo contains Python Jupyter notebooks to perform analysis through clustering and classification on a large dataset of real and fake news. Packages used include Numpy, Scikitlearn, Scipy, Pandas, Matplotlib, Kagglehub and Seaborn. All code was run on mac and linux.

2: The dataset is stored in the DATA directory, and all analysis notebooks are in the SCRIPTS directory. The SCRIPTS directory contains 2 notebooks, one for exploratory data analysis, and the other for modeling. There is a sub-directory, EXTRA_SCRIPTS, which contains scripts used in development but not used in the final analysis. The OUTPUTS folder contains all output plots from the analysis

3: To reproduce the results of this project, the user should run the notebook SCRIPTS/EDA_proj1.ipynb in a python notebook editor, and then run SCRIPTS/Modeling_Final.ipynb, to see the modeling approach taken. The EDA notebook covers how to read in the data from Kaggle, perform basic preprocessing operations, and look at trends between real and fake news articles. The Modeling notebook covers the process of vectorizing text data, clustering the vectorized text, and validating that clustering makes sense. The notebook also performs classification by cluster using logistic regression and linear SVC, and validates the significance of the results using a 1-sample t-test

