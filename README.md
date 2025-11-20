# GenZ Slang NER - BiLSTM + CRF

This project implements a Named Entity Recognition model tailored for **GenZ slang** using a **BiLSTM + CRF** architecture. The entire workflow—including preprocessing, training, evaluation, and inference—is contained in a single `.ipynb` notebook. The dataset is loaded directly from Hugging Face rather than stored locally.

## Features

* BiLSTM encoder with CRF decoding
* Direct Hugging Face dataset integration
* End-to-end NER pipeline in one notebook
* Handles slang-specific entity labels

## Model

The notebook includes embedding preparation, a BiLSTM sequence encoder, and a CRF layer for structured prediction.

## Running the Notebook

Open the `.ipynb` file and execute cells in order to train and evaluate the model.

## Notes

Feel free to adjust the model configuration, labels, or dataset source directly within the notebook.

