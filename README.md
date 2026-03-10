# Transfer Learning Text Classification using Hugging Face

## Overview
This project demonstrates text classification using transfer learning with a pre-trained transformer model from Hugging Face.

## Objective
To classify input text as positive or negative sentiment using a pre-trained model without training from scratch.

## Technologies Used
- Python
- Hugging Face Transformers
- PyTorch

## Model Used
distilbert-base-uncased-finetuned-sst-2-english

This model is pre-trained for sentiment analysis and downloaded from the Hugging Face model hub.

## How to Run
1. Install required libraries:
   pip install transformers torch

2. Run the program:
   python sentiment_classifier.py

## Example
Input:
Artificial intelligence is an advanced technology

Output:
POSITIVE sentiment with confidence score.

## Learning Outcome
This project demonstrates how transfer learning can be used to perform text classification efficiently using pre-trained transformer models.
