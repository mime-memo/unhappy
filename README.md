# The Unhappy Texts
# Description
Sentiment classification is valuable for literary analysis, as sentiment is crucial in literary narratives. It can, for example, be used to investigate a hypothesis in the literary analysis of 19th-century Scandinavian novels that the writing of female authors in this period was characterized by negative sentiment, as this paper shows. In order to enable a data-driven analysis of this hypothesis, we create a manually annotated dataset of sentence-level sentiment annotations for novels from this period and use it to train and evaluate various sentiment classification methods. We find that pre-trained multilingual language models outperform models trained on modern Danish, as well as classifiers based on lexical resources. Finally, in the classifier-assisted corpus analysis, we both confirm and contest the literary hypothesis and further shed light on the temporal development of the trend. Our dataset and trained models will be useful for future analysis of historical Danish and Norwegian literary texts.

#Dataset
The dataset is uploaded to the 'Dataset' directory and is structured as follows:
`train_set.txt: TXT file containing the training set with annotated text for sentiment analysis.
`dev_set.txt: TXT file containing the development set with annotated text for sentiment analysis.
`test_set.txt: TXT file containing the testing set with annotated text for sentiment analysis.
```
@inproceedings{allaith2023sentiment,
title={Sentiment Classification of Historical Literary in {D}anish and {N}orwegian Texts},
author={ALI ALLAITH and Kirstine Nielsen Degn and Alexander Conroy and Bolette S. Pedersen and Jens Bjerring-Hansen and Daniel Hershcovich},
booktitle={The 24rd Nordic Conference on Computational Linguistics},
year={2023},
url={https://openreview.net/forum?id=dszKbb2GH3}
}
```
