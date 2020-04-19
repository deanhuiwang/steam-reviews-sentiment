# Steam Reviews Sentiment Analysis
W266

Tomas Lobo and Dean Wang

April 20, 2020

## Purpose
These notebooks were used for the final project for W266: Natural Language
Processing at UC Berkeley.

In the project, a dataset of reviews text from the Steam games platform were
preprocessed and several different models were used to predict whether the
sentiment expressed in each review was positive or negative.

## Setup
It is recommended to install the packages in `requirements.txt` by running
the following command in a virtual environment:

```
pip install -r requirements.txt
```

## Notebooks
Initial exploration was done on the Steam reviews dataset in
[exploration.ipynb](https://github.com/deanhuiwang/steam-reviews-sentiment/blob/master/exploration.ipynb).

Preprocessing was done on a dataset of Steam reviews retrieved from
[here](https://zenodo.org/record/1000885#.XmJPM5NKhPM). A sample of data from
the larger dataset was used. Data were further split into train, dev, and test
subsets. This was done in
[preprocess-and-split.ipynb](https://github.com/deanhuiwang/steam-reviews-sentiment/blob/master/preprocess-and-split.ipynb).

Baseline models (Naive Bayes and SVM) were fit and evaluated on the preprocessed
data in
[baselines.ipynb](https://github.com/deanhuiwang/steam-reviews-sentiment/blob/master/baselines.ipynb).

The Universal Sentence Encoder model was fit and evaluated on the preprocessed
data in
[steam-reviews-sentiment.ipynb](https://github.com/deanhuiwang/steam-reviews-sentiment/blob/master/steam-reviews-sentiment.ipynb).
