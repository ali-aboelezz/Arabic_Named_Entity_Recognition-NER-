# Arabic Named Entity Recognition (NER) Model - README

## Overview

This repository contains an Arabic Named Entity Recognition (NER) model fine-tuned on the ANERcorp dataset. The model is based on the Hugging Face Transformers library and is designed for identifying named entities in Arabic text. NER is a crucial task in information extraction that involves identifying and classifying entities like persons, organizations, locations, and more within text.

The model is pre-trained on the `aubmindlab/bert-base-arabertv02` architecture and fine-tuned specifically for NER tasks.

## Model Details

- **Model Name**: NER-Arabic-2023
- **Fine-tuned on**: ANERcorp dataset
- **Pre-trained Model**: `aubmindlab/bert-base-arabertv02`
- **Task Type**: Named Entity Recognition (NER)

## Installation

To use the NER model, you need to install the following dependencies:

- Python 3.x
- Hugging Face Transformers library
- PyTorch
- NumPy

You can install these dependencies using the provided `requirements.txt` file or by running `pip install -r requirements.txt`.

## Usage

### Predicting Named Entities

You can use the model to predict named entities in Arabic text. Here's an example:

```python
from your_model_module import predict_sent

text = "الامم المتحدة توجد في مصر"
predict_sent(text)
