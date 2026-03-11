# Li-Chen
This repository contains a coursework mini-project implementing an image captioning model using the Flickr8k dataset.

## Method

- CNN encoder: VGG16 pretrained on ImageNet
- Caption decoder: Embedding + BiLSTM
- Dataset: Flickr8k (8000 images, 5 captions per image)

## Pipeline

1. Extract image features using VGG16
2. Clean and tokenize captions
3. Train a sequence-to-sequence model to generate captions

## Example

Input image → generated caption

## Run

The experiment was implemented in a Jupyter Notebook.
