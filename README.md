# Automatic Sleep Classification

## Introduction

This repository holds the code for training and testing a sleep classification model in Python. The techniques used are CNNs and LSTMs and the input data is the EEG channel of the dataset available [here](https://physionet.org/content/sleep-edfx/1.0.0/). 

The code supports a thesis project that is currently under review for publishing; therefore, currently I am not able to upload the entire paper. However, most of the important ideas and proposals are explained inside the notebooks.

The whole pipeline of the project, from data extraction, to modeling, to output analysis is available and adequatelly documented in the 3 notebooks, which are to be executed in the following order: 1. Data Acquisition --> 2. Classifiers --> 3. Threshold analysis.

## How to run

* The 3 notebooks are implemented in Google Colab. To run, just download the complete repository and upload it into a Google Drive folder. Inside the notebooks, you will find the code to link the Colab session to the Google Drive File System when required. 

* The notebooks were written for a smooth Google Colab execution; however, it should be relatively simple to adapt them to any other Python notebook product (Anaconda, Kaggle, etc).

* **Libraries:** In the Colab environment most libraries are preinstalled. Only 1 library (MNE) is installed inline when required using pip. 

## Methods

* The notebook experiments with 2 versions of CNN and LSTM ensembles. The architecture of the best performing network is as follows:


## Bugs and future work:

* None found. 

* Any feedback will be well taken and appreciated! 



