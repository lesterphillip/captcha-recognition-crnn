# PyTorch Captcha Recognition System
A simple Python Notebook detailing the process of recognizing a 10-character captcha image using a CNN to process the image and GRU to process the sequence using PyTorch. The loss is calculated using CTC Loss.

## Usage
The Kaggle Dataset used for this can be found [here.](https://www.kaggle.com/aadhavvignesh/captcha-images)
Any other dataset should also work with this model and retrained, assuming that all of the samples have equal amounts of captcha characters.

## References
I also used Abhishek's tutorial on captcha recognition and used it as a starter for this notebook. You can find his tutorial [here.](https://www.youtube.com/watch?v=IcLEJB2pY2Y) I've detailed some of my changes in the notebook such as:
- refactoring the code as a notebook
- using a different dataset
- adding early stopping
- model performance analysis

