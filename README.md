# eye_for_the_blind

## Problem Statement

**Problem statement:** In this capstone project, I aim to design a deep learning model that describes the contents of an image in the form of speech. This is achieved through caption generation with an attention mechanism applied on the Flickr8K dataset. The primary application for such a model benefits visually impaired individuals, allowing them to interpret any image through auditory means. The caption, produced by a CNN-RNN model, is then vocalized using a text-to-speech library.

This project encapsulates applications of both deep learning and natural language processing. The image features are extracted using a CNN-based encoder, which is subsequently decoded by an RNN model.

The inspiration for this project stems from the extended application of the "Show, Attend and Tell: Neural Image Caption Generation with Visual Attention" paper.

The dataset, sourced from the Kaggle platform, comprises sentence-based image descriptions. It features a list of 8,000 images, each paired with five distinct captions that meticulously describe the prominent entities and occurrences within the image.

## Project Pipeline

My approach to this project can be concisely segmented into the following key phases:

1. **Data Understanding:** At this juncture, I'll load and familiarize myself with the data's structure and representation.
2. **Data Preprocessing:** Here, I'll format both images and captions to meet the desired specifications.
3. **Train-Test Split:** The next step involves amalgamating both images and captions to carve out the train and test datasets.
4. **Model Building:** This pivotal stage entails crafting the image captioning paradigm, encompassing the construction of the Encoder, Attention, and Decoder models.
5. **Model Evaluation:** I'll assess the models using greedy search and gauge performance through the BLEU score.
