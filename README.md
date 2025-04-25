# LPC Speaker Identification

This project focuses on classifying speech segments by speaker using Linear Predictive Coding (LPC) based cepstral coefficients. The data consists of time series blocks with varying lengths, each representing frames of a single speaker's utterance.

## 🔍 Project Overview

- **Task**: Speaker classification (9 male speakers)  
- **Input**: Time series of 12-dimensional LPC cepstrum features  
- **Goal**: Accurately predict the speaker for each block  
- **Data**: Provided as `train.txt`, `test.txt`, and `train_block_labels.txt`

## 📁 Files

- `train.txt` – Time series data for training  
- `test.txt` – Unlabeled time series data for prediction  
- `train_block_labels.txt` – Mapping of training blocks to speaker labels  
- `jupyter notebook` – Experiments with feature engineering and models  
## 🚀 Methods

- Time series preprocessing and block segmentation  
- Classification using traditional ML models  

## 📊 Results

Model performance is evaluated using classification accuracy.

