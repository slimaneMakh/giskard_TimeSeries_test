# Giskard time series technical test
We present in this repository our work for Giskard technical test on creating a time-series oriented inspection tool

## Requirements
Please install all required packages listed in `requirements.txt`:
```bash
pip install requirements.txt
```

##  Context
This work was made in 2019 for a contest on time series anomaly detection on sensor data. 

We include the poster we present for this contest [here](poster_airbus.pdf).

## Code
We present a part of the work in this [notebook](Code/Autoencoder_based_anomaly_detection.ipynb). 

In this notebook we first load the dataset on which was performed a PCA to reduce dimensions while keeping 0.99% variance.
We train an autoencoder on normal train data then analyse reconstruction error and latent representation of both normal and abnormal test data. 
