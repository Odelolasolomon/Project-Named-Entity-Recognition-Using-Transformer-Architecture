# Project-Named-Entity-Recognition-Using-Transformer-Architecture

This project aims to develop a Transformer model for Named Entity Recognition (NER), an essential task in Natural Language Processing (NLP). The goal of NER is to accurately identify and classify named entities in text, such as person names, locations, and organizations. Recognizing these entities has applications in information retrieval, content recommendation, and customer support.

## Project Overview

NER is a sequence labeling task where each token in the text is assigned a label. This project leverages the Transformer architecture, as introduced in the paper "[Attention is All You Need](https://arxiv.org/abs/1706.03762)" by Vaswani et al. Transformers utilize self-attention mechanisms to capture long-range dependencies between tokens in a sequence, making them highly effective for sequence-to-sequence tasks such as NER.

## Dataset

The dataset used in this project is the **Broad Twitter Corpus (BTC)**. This dataset consists of tweets annotated for named entities and represents various activities. It is licensed under the CC-BY 4.0 license. The dataset has several sections, typically with section F used as the test set and the remaining sections for training.

You can learn more about the dataset here: [BTC Dataset Information](https://example-link-to-dataset.com)

## Model Architecture

The model implemented in this project is based on the Transformer architecture. Key components include:

- **Multi-Head Self-Attention:** Allows the model to focus on different parts of the sentence simultaneously.
- **Positional Encoding:** Provides the model with information about the position of tokens in a sequence.
- **Feedforward Neural Network:** Applies transformations to the input using fully connected layers.

## Training Process

The training process involves:

1. Preprocessing the dataset and tokenizing the text.
2. Creating attention masks to handle variable-length sequences.
3. Fine-tuning the Transformer model on the NER task.
4. Evaluating the model on the test set.

## Results

The model achieved significant improvements in recognizing named entities in the Twitter dataset, with promising accuracy and F1-score metrics. Detailed results and model performance metrics can be found in the [Results Section](#results-section).

## Installation

To run this project, clone the repository and install the necessary dependencies



