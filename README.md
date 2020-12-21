# Simple walktrough for an named entitiy recognition (NER) setup for the German language

Different embeddings get benchmarked, that are possibly good for German NER. As stated in the [paper](paper/evaluation_of_deep_learning_methods.pdf), a combination of BERT embeddings and Flair embeddings provides new best performance on the GermEval-14 NER dataset (F1-score of 86.62).

## Setup
Flair Experiments: [Flair](https://github.com/flairNLP/flair) and [Google Colab](https://colab.research.google.com)

BERT Experiments: [Transformers](https://github.com/huggingface/transformers) and [Google Colab](https://colab.research.google.com)

## Datasets

The dataset are [Conll-03](https://www.clips.uantwerpen.be/conll2003/ner/) and [GermEval-14](https://sites.google.com/site/germeval2014ner/data).
BIOES and BIO/IOB formats are considered in the evaluation.



