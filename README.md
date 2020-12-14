# Sentiment Analysis performance benchmark

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IhabBendidi/sentiment_embeddings/blob/main/sentiment_embeddings.ipynb)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/IhabBendidi/sentiment_embeddings/blob/master/LICENSE)

**Authors :** *Ihab Bendidi*, *Yousra Bourkiche*, *Clément Siegrist*, *Kaouter Berrahal*

In general, documents with similar sentiments, would be close to each other in the embeddings feature space. This can become another method to judge the performance of sentiment analysis models.

In this work, we aim to perform a benchmark of recent sentiment analysis works and models, reproduce their results, and judge their performance in comparison to baseline methods.

## Outline 

The following work in made on a jupyter notebook, that you can find [here](https://github.com/IhabBendidi/sentiment_embeddings/blob/main/sentiment_embeddings.ipynb), or open in Colab [here](https://colab.research.google.com/github/IhabBendidi/sentiment_embeddings/blob/main/sentiment_embeddings.ipynb).

**I - Processing & Exploratory Data Analysis**
- *Understanding the data*
- *Text Preprocessing*

**II - Sentiment classification models**
- *Bert Model*
- *LSTM recurrent model*
- *Baseline method : textblob*

**III - Document Embeddings**
- *Training doc2vec*
- *Doc2vec sentiment classifier*

**IV - Model performance visualisation**
- *Bert model*
- *LSTM model*
- *Logreg model*
- *Textblob*

You can also find `.pdf`report with code [here](https://github.com/IhabBendidi/sentiment_embeddings/blob/main/sentiment_embeddings.pdf).

### Installation

This was tested on Ubuntu 20.04 with Python 3.7, but should run on any device and any python 3 version.

Before running it, make sure to install dependencies, by running in terminal :

```
pip install -r requirements.txt
```

On Google colab, you would need to import the `requirements.txt` file, and the `tweets.csv` dataset to your colab session.
