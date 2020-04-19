# oversampling_vae
A simple code that shows how to deal with unbalanced data sets and use VAEs to generate samples from the minority class

# Getting and scaling data
This repo contains the jupyter notebook `main.ipynb` that performs all the tasks in one place.

The first step is to get the data from kaggle.

https://www.kaggle.com/mlg-ulb/creditcardfraud

Then scale each variables, split the data into train and test.

# Train the VAEs
We are going to use a very simple VAE. We will separate the data that corresponds to the fradulant transactions. We train a VAE on the training set only.

Then we sample from the model until the dataset is balanced.

# Augment the data
Augment the training data only and train a classifier on this new data. We will only use boosting classifier here.

# instructions

first install the required packages

`pip install -r requirements.txt`

Downlaod the data set from the kaggle and place it in the directory.