# Stat-ML-Project
Code folder includes all the coding (jupyter notebook) files for both preprocessing and model traing.
Data folder contains all the data we used during the project.
Models folder contains the gru model we training for reproducing our result if required. 

In order to reproducde the results, please follow these steps:
1. Go to https://grouplens.org/datasets/movielens/20m/ and download ml-20m.zip and unzip the file to data/raw data
2. keep only movies.csv and rating.csv
3. Run data_cleaning.ipynb to reproducing clean data inside data/clean_data
4. Run StatML_project.ipynb for reproducing results of model 1 (KNN) and model 2 (SVD)
5. Run GRU.ipynb for reproducing results of model 3 (GRU) (this may take up to 5 hours !!!)
