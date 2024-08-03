# Hindi Text Summarization Using Neural Networks

## Introduction

This repository contains the code and models for the Hindi Text Summarization project developed as part of the CSE556: Natural Language Processing course. Our project focuses on the challenge of text summarization for Hindi, a language rich in syntax and morphological features but lacking in substantial NLP resources.

## Motivation

The primary goal of this project is to create effective summarization tools for Hindi text, which can be crucial for various applications like news digestion, academic research, and efficient business communications. Given the complexity and resource scarcity in Hindi NLP, our work aims to contribute valuable insights and tools to the community.

## Models

We explored three different models in this project:
- **IndicBART**: A seq2seq model fine-tuned for summarization tasks in Indian languages.
- **Transformer Model**: A custom implementation designed specifically for the nuances of Hindi text.
- **MT5**: A multilingual model adapted for Hindi summarization to assess its performance against more specialized models.

## Dataset

The `hindi_train.csv` dataset used in this project comprises around 20,000 article-summary pairs, offering a substantial volume for training and evaluating our models. These articles span a variety of topics, providing diverse linguistic features for the models to learn from.

## Setup and Usage

### Prerequisites
- Python 3.8+
- PyTorch 1.8+
- Transformers Library

## Results

Our findings indicated that IndicBART outperformed the other models on various performance metrics, including BERT and ROUGE scores. Detailed results and performance metrics are available in the `results` section of this repository.

## Future Work

Further improvements could include expanding the dataset, incorporating more complex model architectures, or applying transfer learning techniques from models trained on other languages.

# Copyright and License

## Copyright (c) 2024, Nikhil Suri

## All rights reserved

This code and the accompanying materials are made available on an "as is" basis, without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

## No Licensing
This project is protected by copyright and other intellectual property laws. It does not come with any license that would permit reproduction, distribution, or creation of derivative works. You may not use, copy, modify, or distribute this software and its documentation without express written permission from the copyright holder.

## Contact Information
For further inquiries, you can reach me at nikhil21268@iiitd.ac.in
