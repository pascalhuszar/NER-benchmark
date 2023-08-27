# Simple walktrough for a named entitiy recognition (NER) setup for the German language

Different embeddings for Named Entity Recognition (NER) in German text are benchmarked. As stated in my bachelor [thesis](paper/evaluation_of_deep_learning_methods.pdf), a combination of BERT embeddings and Flair embeddings yields new best performances on the GermEval-14 NER dataset (F1-score of 86.62).

## Setup
Flair Experiments: [Flair](https://github.com/flairNLP/flair) and [Google Colab](https://colab.research.google.com/drive/1FUn0M66DmPuE1oQm4zIo0us0EUziFwtg) 

BERT Experiments: [Transformers](https://github.com/huggingface/transformers) and [Google Colab](https://colab.research.google.com/drive/1nE3zoSC2HpW_srsQ-St5PRtCBvp_OCij)

## Datasets

BIOES and BIO/IOB formats are considered in the evaluation.

The datasets used in my benchmark are [Conll-03](https://www.clips.uantwerpen.be/conll2003/ner/) and [GermEval-14](https://sites.google.com/site/germeval2014ner/data). Additionally, i compared several embeddings on a complaint dataset in my bachelor thesis. Unfortunately, this dataset is not public, but the performance can be found in the thesis. 





