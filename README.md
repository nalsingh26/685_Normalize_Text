# Normalizing SMS text using Language Models

In this project, we have written code to create a dataset that mimics SMS languages. We add noise similar to that found in SMS texts to any textual dataset, to obtain an SMS like dataset with grammatically correct ground truth labels which facilitates supervised learning and provides an automated way to check model performance on the task. The main task this dataset serves is the normalization of SMS texts, or converting unnatural words in SMS messages into their normalized, grammatically correct form.

There are several types of text abnormalities found in SMS texts, like:


We provide an algorithm that randomly introduces all these types of noises into the dataset, to a random number of words. One word may also have multiple types of noise added to itself. Once this dataset is ready, we perform the task of normalization.

We have explored 2 different approaches for normalizing noisy text data - 

1. Masked Language Model Based Approach using BERT 

2. Sequence-to-Sequence approach using T5. 

In our experiments, we have also evaluated performance improvements achieved on downstream task by denoising textual data.

The code, dataset, trained models and annotations for our project are present in this repository.
* [Dataset Creation](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Dataset_creation_AND_Masking_Model.ipynb)
* [Evaluation of Masking Strategies](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Dataset_creation_AND_Masking_Model.ipynb)
* [Fine-tuning T5 for text normaliztion](https://github.com/nalsingh26/685_Normalize_Text/blob/main/T5_Seq2Seq_Approach.ipynb)
* [Masked Language Pipeline](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Masked_Language_Modeling_Approach.ipynb)
* [Evaluation on Downstream Task of Sentiment Analysis](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Downstream_Task_Evaluation.ipynb)
* The [training/test data and base data for evaluation](https://github.com/nalsingh26/685_Normalize_Text/tree/main/dataset)
* The [normalized data from the models for sentiment analysis](https://github.com/nalsingh26/685_Normalize_Text/tree/main/predicted_data_and_annotations)
* Annotation of the [generated dataset](https://github.com/nalsingh26/685_Normalize_Text/blob/main/predicted_data_and_annotations/unnormalized_data_annotation.pdf) and [normalized NUS SMS Corpus](https://github.com/nalsingh26/685_Normalize_Text/blob/main/predicted_data_and_annotations/smstext%20-%20annotation.pdf)

The finetuned, pretrained and optimized models can be found here:
- [Fine-tuned T5 model](https://drive.google.com/drive/folders/10XS4TSvAsMEsVMM_lZgsWD6yTxAbuX9C?usp=sharing)
- [Fine-tuned token classification model](https://drive.google.com/drive/folders/1-NhWRWHlriqtXccjEjuQckOjb5eH7VoS?usp=sharing)
- [Trained ML model for similarity weights](https://drive.google.com/file/d/1-1JLnKYLrW-fokcLyNSwKYuRi2_FY2o8/view?usp=sharing)
- [Pre-trained model used for Downstream Tasks](https://drive.google.com/drive/folders/11ov6WPeaAjTwExbVYQ1JwbgrOTcXbBz6?usp=sharing)

This project was completed as a part of COMPSCI 685 at the University of Massachusetts, Amherst and has the following contributors:
* [Fenil Doshi](https://github.com/fenil25)
* [Jimit Gandhi](https://github.com/jimitgandhi)
* [Nalini Singh](https://github.com/nsingh261)
* [Ruturaj Gujar](https://github.com/Ruturaj123)
