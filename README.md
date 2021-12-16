# Normalizing SMS text using Language Models

In this project, we have written code to add noise similar to that found in SMS texts to any textual dataset. This gives us a SMS like dataset with grammatically correct ground truth labels which facilitates supervised learning and provides an automated way to check model performance on the task.

We have explored 2 different approaches for normalizing noisy text data - (1) Masked Language Model Based Approach using BERT and (2) Sequence-to-Sequence approach using T5. In our experiments, we have also evaluated performance improvements achieved on downstream task by denoising textual data.

The code, dataset, trained models and annotations for our project are present in this repository.
* [Dataset Creation](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Dataset_creation_AND_Masking_Model.ipynb)
* [Evaluation of Masking Strategies](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Dataset_creation_AND_Masking_Model.ipynb)
* [Fine-tuning T5 for text normaliztion](https://github.com/nalsingh26/685_Normalize_Text/blob/main/T5_Seq2Seq_Approach.ipynb) : [Fine-tuned model](https://drive.google.com/drive/folders/10XS4TSvAsMEsVMM_lZgsWD6yTxAbuX9C?usp=sharing)
* [Masked Language Pipeline](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Masked_Language_Modeling_Approach.ipynb)
* [Evaluation on Downstream Task of Sentiment Analysis](https://github.com/nalsingh26/685_Normalize_Text/blob/main/Downstream_Task_Evaluation.ipynb) : [Pre-trained model used](https://drive.google.com/drive/folders/11ov6WPeaAjTwExbVYQ1JwbgrOTcXbBz6?usp=sharing)
* The [training/test data and base data for evaluation](https://github.com/nalsingh26/685_Normalize_Text/tree/main/dataset)
* The [normalized data from the models for sentiment analysis](https://github.com/nalsingh26/685_Normalize_Text/tree/main/predicted_data_and_annotations)
* Annotation of the [generated dataset](https://github.com/nalsingh26/685_Normalize_Text/blob/main/predicted_data_and_annotations/unnormalized_data_annotation.pdf) and [normalized NUS SMS Corpus](https://github.com/nalsingh26/685_Normalize_Text/blob/main/predicted_data_and_annotations/smstext%20-%20annotation.pdf)
