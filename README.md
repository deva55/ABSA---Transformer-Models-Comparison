# ABSA - Transformer Models Comparison

## 📌 Project Overview

This project focuses on Aspect-Based Sentiment Analysis (ABSA) using multiple machine learning and transformer-based models. The goal is to identify specific aspects from restaurant review text and classify the sentiment associated with each aspect.

The project compares traditional and advanced NLP approaches, including SVM, BERT, RoBERTa, GPT-based models, and lexicon-based methods, to evaluate their performance in aspect extraction and sentiment classification.

## 🎯 Objective

The main objective of this project is to compare different NLP models for Aspect-Based Sentiment Analysis and understand how transformer-based models perform against traditional machine learning approaches.

This helps analyze customer opinions at a deeper level instead of only predicting overall review sentiment.

## 🧠 Models Used

- Support Vector Machine (SVM)
- Lexicon-based sentiment approach
- BERT
- RoBERTa
- GPT-based model


## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Natural Language Processing
- Machine Learning
- Transformer Models
- BERT
- RoBERTa
- GPT
- Pandas
- Scikit-learn
- Hugging Face Transformers

## 📂 Project Structure

```text
ABSA - TransformerModels/
│
├── Code/
│   ├── ABSA_BERT.ipynb
│   ├── ABSA_RoBERTa.ipynb
│   ├── BERT_OverallSentiment.ipynb
│   ├── DataSETPreprocessing_Unlabeled_Labeled.ipynb
│   ├── Finetuning_BERT_GPT.ipynb
│   ├── GPT_OverallSentiment.ipynb
│   ├── Lexicon_ABSA.ipynb
│   ├── RoBERTa_OverallSentiment.ipynb
│   └── SVM_ABSA.ipynb
│
├── Result/
│   ├── BERTpredicted_aspects.csv
│   ├── BERTGPTpredicted_aspects_with_sentiment.csv
│   ├── RoBERTApredicted_aspectsFinal.csv
│   └── Overall sentiment prediction files
│
├── Presentation/
│   └── Project presentation files
│
├── Fine-Tuning Models/
│   └── Fine-tuning notebooks
│
├── .gitignore
└── README.md