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
- `notebooks/` – Experiments with feature engineering and models  
- `models/` – Trained models and evaluation scripts  

## 🚀 Methods

- Time series preprocessing and block segmentation  
- Feature extraction using statistical and shape-based techniques  
- Classification using traditional ML and deep learning models  

## 📊 Results

Model performance is evaluated using classification accuracy. More details in the [notebooks](./notebooks) folder.

## 🛠️ Requirements

```bash
pip install -r requirements.txt
