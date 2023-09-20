# bybynOCR ᜊᜌ᜔ᜊᜌᜒᜈ᜔
An OCR model for character-level recognition of Baybayin, the pre-colonial script of the Tagalog Language. Soon, I plan to implement full Scene Text Detection in images.

## Introduction

As a Filipino-American growing up in the United States, I, like many others, grew up unaware of Baybayin or any existing writing system from the Philippines. After attending college and becoming more curious about my own culture, I have had a fascination with the script not only as a writing system, but also how it relates to the history of colonization in the Philippines all the way to the current perceptions and attitudes towards pre-colonial, post-colonial, and current Philippine culture.

Although Baybayin is implemented into the Google Keyboard, and the character set exists in Unicode and UTF-8, I have only found a few research papers looking into character recognition for the script.

This project is my contribution to continuing the use of Baybayin by making it more accessible with Optical Character Recognition.

## Current Technical Features
- Uses Keras' Convolutional Layers to train a CNN Model to classify input and recognize the characters

## Planned Technical Features
- Increasing accuracy by experimenting with other architectures
- Implementing Full Text Detection and Extraction
- Tagalog spellcheck using either Levenshtein Distance or a language model to help correct any inaccuracies

## Installation
### Demo
Online demo coming soon!

### Current Instructions to Install Locally
1. Clone the repo and open in Google Colab or Jupyter Notebook
2. Add a 28x28 .jpg image to root directory of your handwritten Baybayin character and add the path to the input cell
3. Run the cells one after another until the inference step
