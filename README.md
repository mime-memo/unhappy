# Sentiment Classification of Historical Literary in Danish and Norwegian Texts
## Description
This project describes a study on sentiment classification in literary analysis of 19th-century Scandinavian novels by female authors. We create a dataset, train and evaluate sentiment classification methods, and use pre-trained language models to confirm and contest a literary hypothesis that the writing of female authors in that period was characterized by negative sentiment. The dataset and trained models are expected to be valuable for future analysis of historical Danish and Norwegian literary texts.

## Dataset
The dataset is uploaded to the `dataset` directory and is structured as follows:

1. `train_set.txt`: TXT file containing the training set with annotated text for sentiment analysis.
2. `dev_set.txt`: TXT file containing the development set with annotated text for sentiment analysis.
3. `test_set.txt`: TXT file containing the testing set with annotated text for sentiment analysis.


Each file contains two columns (tab separated) where the first column is the sentence and the second column is the sentimen annoation (1=positive, 0=neutral, and 2=negative)

## Python Code
The Python code file (`Danish_Sentiment_Analysis.ipynb`) provided in this repository demonstrate how to use the historical Danish and Norwegian sentiment analysis dataset. The code includes examples of loading the dataset, preprocessing the text data, and fine-tuning and training a sentiment analysis models.

## Usage
To use the dataset and code, follow these steps:

1. Clone or download this GitHub repository.
2. Access the dataset files in the `dataset` directory and the Python code file.
3. Use the dataset files for training, development, and testing of sentiment analysis models in your research or applications.
4. Run the Python code files using your preferred IDE or Python environment to understand how to load, preprocess, and analyze the historical text data.

## License
The dataset and code in this repository are released under the [Creative Commons Attribution 4.0 International license](http://creativecommons.org/licenses/by/4.0/).

## Citation
For more details about the sentiment annoatation and classification, please read further in [the following paper](https://openreview.net/forum?id=dszKbb2GH3):

```
@inproceedings{allaith2023sentiment,
title={Sentiment Classification of Historical Literary in {D}anish and {N}orwegian Texts},
author={Ali Al-Laith and Kirstine Nielsen Degn and Alexander Conroy and Bolette S. Pedersen and Jens Bjerring-Hansen and Daniel Hershcovich},
booktitle={The 24rd Nordic Conference on Computational Linguistics},
year={2023},
url={https://openreview.net/forum?id=dszKbb2GH3}
}
```
