# ADFNet: Adaptive Dynamic Feature Network for IoT Intrusion Detection

This repository contains the official implementation of the ADFNet model proposed in the paper:

"ADFNet: A Lightweight Adaptive Multi-Exit Deep Learning Model for IoT Intrusion Detection"

## Dataset
This work uses the CICIoT2023 dataset:
https://www.unb.ca/cic/datasets/iotdataset-2023.html

Due to licensing restrictions, the dataset is not included in this repository.

## Requirements
Python 3.9  
numpy==1.23.5
pandas==1.5.3
scikit-learn==1.2.2
tensorflow==2.9.1
joblib==1.2.0
psutil==5.9.4

## Installation

Install the required dependencies using:

pip install -r requirements.txt


## Usage

1. Run `input.ipynb` to preprocess the CICIoT2023 dataset and extract a random 10% subset.
2. Run `ADFNet_iot.ipynb` in Jupyter Notebook to train and test the ADFNet model.

## Reproducibility

All reported results in the paper can be reproduced by sequentially running `input.ipynb` and `ADFNet_iot.ipynb` using the same configuration.


## License
MIT License
