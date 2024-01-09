# Punctuation Restoration with BERT and Nemo

## Overview
This project explores the effectiveness of two distinct models, Fine-tuned BERT and Pretrained Nemo, for punctuation restoration. Punctuation restoration is a critical aspect of natural language processing that enhances text readability and coherence. The project includes the implementation of a BERT model fine-tuned for the specific task, along with the utilization of a pretrained Nemo model. The primary objective is to compare their performance based on the Jaccard similarity metric. Due to computational constraints, a subset of the "NLP Mental Health Conversations" dataset is used for training, validation, and testing.

## Project Structure

### 1. `Fine-tuned_BERT_Punctuation_Restoration.ipynb`
   - This Jupyter Notebook contains the code for data preprocessing, model architecture, training, and evaluation of the Fine-tuned BERT model. It showcases the process of cleaning the dataset, splitting it into subsets, and training the BERT model for punctuation restoration.

### 2. `Nemo_Punctuation_Restoration.ipynb`
   - The second Jupyter Notebook focuses on implementing the Pretrained Nemo model for punctuation restoration. It includes data preprocessing, loading the pretrained model, and evaluating its performance on the same dataset.

### 3. `Project_Report.pdf`
   - The project report provides an in-depth overview of the methodology, model architectures, training procedures, and results. It also highlights limitations and areas for improvement.

### 4. `README.md`
   - This README file serves as a guide for understanding the project structure, its objectives, and how to replicate the experiments. It includes information on data preprocessing, model implementation, and the comparison process.

## Requirements
- Python 3.7 or higher
- Jupyter Notebook
- PyTorch
- Transformers
- Nemo Toolkit
- Matplotlib
- TQDM

## How to Use
1. Clone the repository to your local machine.
2. Open and run the Jupyter Notebooks (`Fine-tuned_BERT_Punctuation_Restoration.ipynb` and `Nemo_Punctuation_Restoration.ipynb`) to replicate the experiments.
3. Refer to the project report for a detailed understanding of the methodology, results, and limitations.

## Acknowledgments
- The project utilizes the "NLP Mental Health Conversations" dataset, available on Kaggle.

## Authors
- [Rishabh Khanna](https://github.com/RishKhanna)

Feel free to contribute, report issues, or suggest improvements!
