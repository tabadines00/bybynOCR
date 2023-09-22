# bybynOCR ᜊᜌ᜔ᜊᜌᜒᜈ᜔
An OCR model for character-level recognition of Baybayin, the pre-colonial script of the Tagalog Language. Soon, I plan to implement full Scene Text Detection in images.
[Online Demo](http://thomasabadines.s3-website-us-west-1.amazonaws.com/BybynDemo/index.html) (Works on Mobile!)

![demo](https://github.com/tabadines00/bybynOCR/assets/35116935/65f40554-37bc-4d4e-9404-65213b107aa8)

## Introduction

As a Filipino-American growing up in the United States, I, like many others, grew up unaware of Baybayin or any existing writing system from the Philippines. After attending college and becoming more curious about my own culture, I have had a fascination with the script not only as a writing system, but also how it relates to the history of colonization in the Philippines all the way to the current perceptions and attitudes towards pre-colonial, post-colonial, and current Philippine culture.

Although Baybayin is implemented into the Google Keyboard, and the character set exists in Unicode and UTF-8, I have only found a few research papers looking into character recognition for the script.

This project is my contribution to continuing the use of Baybayin by making it more accessible with Optical Character Recognition.

## Current Technical Features
- Uses Keras' Convolutional Layers to train a CNN Model to classify input and recognize the characters

## Dataset and Resources
- [Handwritten Baybayin Kaggle Dataset by James Arnold Nogra](https://www.kaggle.com/datasets/jamesnogra/baybayn-baybayin-handwritten-images)

## Planned Technical Features
- Increasing accuracy by experimenting with other architectures
- Implementing Full Text Detection and Extraction on Images
- Tagalog spellcheck using either Levenshtein Distance or a language model to help correct any inaccuracies

## Installation
### Demo
[Online Demo](http://thomasabadines.s3-website-us-west-1.amazonaws.com/BybynDemo/index.html) (Works on Mobile!)

### Instructions to Install Locally
The trained model and test images are located in the .tar file. Choose a test image by replacing the path in the designated cell.
1. Clone the repo and open in Google Colab or Jupyter Notebook
2. Run the cells in the Model Inference section
3. Run the cells one after another until the inference step
4. The model will predict a character based on your chosen image!
