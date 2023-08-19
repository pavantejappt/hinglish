# hinglish translation models
## Model 1: Single Layer LSTM Translator

### Overview

Model 1 implements a translation model using a single-layer LSTM (Long Short-Term Memory) architecture. This model is designed to translate English sentences to Hindi. However, it has encountered challenges related to underfitting and a high number of trainable parameters, leading to suboptimal translation performance.

### Usage

1. Clone this repository to your local machine:

'''bash
git clone https://github.com/pavantejappt/hinglish.git


Install the required dependencies:
pip install -r requirements.txt

Load the LSTM model and use the predict_sentence function to translate English sentences to Hindi.



Model 2: Hugging Face Meta Translator
Overview
Model 2 leverages the Hugging Face Transformers library to implement a meta translator that utilizes a pre-trained transformer model for translation tasks. This model benefits from a well-established architecture and avoids the challenges faced by the LSTM model.

Usage
Clone this repository to your local machine:
git clone https://github.com/pavantejappt/hinglish.git

Load the pre-trained meta translator using the Hugging Face Transformers library and translate English sentences to Hindi.
Dependencies
Both models require the following dependencies:

TensorFlow
Pandas
Numpy
Pickle
Seaborn

Acknowledgments
Both models are the result of efforts inspired by various online tutorials, documentation, and research papers on machine translation. Special thanks to the creators of the IITB English-Hindi dataset for providing the training data.





