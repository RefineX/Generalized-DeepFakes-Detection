# Chapter 8: Audio Deep-Fakes Detection

## 8.3 Dataset Curation
### 8.3.1 Feature-Based Datasets
Notebooks used:
1. [audio_feature_extractor.ipynb](audio_feature_extractor.ipynb)
2. [audio_lstm.ipynb](audio_lstm.ipynb)

The notebooks curate the datasets pertaining to the feature-based approach.
### 8.3.2 Image-Based Datasets 
Notebook used: [create_mel_spec_and_amp_plot_datasets.ipynb](create_mel_spec_and_amp_plot_datasets.ipynb)

The notebooks curate the datasets pertaining to the image-based approach.
## 8.4 Training
Notebooks to train the neural-network based architectures.
### 8.4.1 Feature-Based approach
Notebook used: [ASV_LSTM_train.ipynb](ASV_LSTM_train.ipynb)
### 8.4.2 Image-Based approach 
Notebook used: [ASV_CNN_train.ipynb](ASV_CNN_train.ipynb)
## 8.5 Results 
Notebook used: [ASV_Detection.ipynb](ASV_Detection.ipynb)

Notebook to train the SVM and display the results of all the models.

Model files:
1. [lstm_model.h5](lstm_model.h5)
2. [mel_spec_model.h5](mel_spec_model.h5)
3. [amp_plot_model.h5](amp_plot_model.h5)

## 8.6 Feature Importance Analysis for Averaged Features Dataset
Notebook used: [audio_feature_importance.ipynb](audio_feature_importance.ipynb)

This notebook examines the features in the averaged features dataset and computes the importance of said features in the task of classification using various methods.
