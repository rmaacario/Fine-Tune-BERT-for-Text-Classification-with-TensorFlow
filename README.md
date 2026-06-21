# Fine-Tune BERT for Text Classification with TensorFlow

**A hands-on notebook for fine-tuning a pretrained BERT model for text classification
using TensorFlow 2 and TensorFlow Hub.**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rmaacario/Fine-Tune-BERT-for-Text-Classification-with-TensorFlow/blob/main/Fine_Tune_BERT_for_Text_Classification_with_TensorFlow.ipynb)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org)

> An updated version of the Coursera Guided Project
> [*Fine-Tune BERT for Text Classification with TensorFlow*](https://www.coursera.org/projects/fine-tune-bert-tensorflow/),
> reworked to run with current versions of TensorFlow and TensorFlow Hub.

---

## Overview

This repository walks through the full workflow of adapting a pretrained Transformer to a
downstream text-classification task — from raw text to a fine-tuned classifier — using the
`tf.data` API and TensorFlow Hub.

The pretrained encoder is
[`bert_en_uncased_L-12_H-768_A-12`](https://tfhub.dev/tensorflow/bert_en_uncased_L-12_H-768_A-12/2)
from TensorFlow Hub (BERT-Base: 12 layers, 768 hidden units, 12 attention heads).

## What it covers

- Building efficient TensorFlow input pipelines for text with the `tf.data` API
- Tokenizing and preprocessing text into BERT's expected input format (input ids, masks, segment ids)
- Assembling a classification model on top of the BERT encoder
- Fine-tuning end-to-end and evaluating the classifier

## Quick start

The easiest way to run it is in Colab (GPU recommended) — click the badge above.

To run locally:

```bash
git clone https://github.com/rmaacario/Fine-Tune-BERT-for-Text-Classification-with-TensorFlow.git
cd Fine-Tune-BERT-for-Text-Classification-with-TensorFlow

pip install tensorflow tensorflow-hub tensorflow-text
jupyter notebook Fine_Tune_BERT_for_Text_Classification_with_TensorFlow.ipynb
```

## Credits

Based on the Coursera Guided Project by Snehan Kekre, updated here for compatibility with
current TensorFlow / TF-Hub releases.

## Author

**Rafael Macário Fernandes** — NLP Engineer & PhD candidate, University of São Paulo.
[Portfolio](https://rmaacario.github.io/portfolio) · [GitHub](https://github.com/rmaacario)
