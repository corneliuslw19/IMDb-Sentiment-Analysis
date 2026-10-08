# IMDb Sentiment Analysis
A Natural Language Processing (NLP) project that classifies IMDb movie reviews as positive or negative using traditional machine learning and neural network approaches.

## Project Overview
This project compares three approaches to sentiment classification:

TF-IDF + Multinomial Naive Bayes** — a traditional machine learning baseline.
GloVe + Logistic Regression** — uses pre-trained word embeddings for text representation.
Keras Neural Network** — uses an embedding layer and dense layers for sentiment classification.

The project explores text preprocessing, feature representation, model training and performance evaluation.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- GloVe word embeddings

## Model Performance
| Model | Test Accuracy |
|---|---|
| TF-IDF + Naive Bayes | 86.16% |
| GloVe + Logistic Regression | 79.98% |
| Keras Neural Network | 87.26% |

The neural network achieved the highest recorded test accuracy in the experiments.

## Dataset
The project uses the IMDb Dataset of 50K Movie Reviews, containing positive and negative movie reviews.

The dataset is available from:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

Download `IMDB Dataset.csv` and place it in the project folder before running the notebook.

## Pre-trained Word Embeddings

The GloVe-based model uses 100-dimensional pre-trained word vectors.

GloVe embeddings are available from:

https://nlp.stanford.edu/projects/glove/

Download the GloVe 6B dataset, extract `glove.6B.100d.txt`, and place it in the project folder.

## Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Running the Project

1. Download the IMDb dataset and GloVe embeddings.
2. Place both files in the project folder.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `CM3060_Natural_Language_Processing.ipynb`.
5. Run the notebook cells in order.

## Evaluation

The models were evaluated using classification accuracy, classification reports and confusion matrices.

The project demonstrates how different text representation and classification methods affect sentiment-analysis performance.

## Academic Context

Developed as part of the University of London Computer Science programme, CM3060 Natural Language Processing module.
