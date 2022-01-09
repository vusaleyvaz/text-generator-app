# Text Generator Application with GPT2, Huggingface Transformers, Tensorflow and Holoviz Panel

## Introduction

This is a text generator application that visualizes probability distribution for top-N tokens for the model's dictionary and allows generating texts, by having an initial prompt and using different decoding strategies.

The application was built using the open-source Panel library, which allows to build and deploy applications through jupyter notebook. The language models are taken from the Huggingface library. For the showcase, the application was built using GPT-2 models. Python, Tensorflow, and other common Python libraries were used to build the required functions.


##  GPT2
For this project, I used Huggingface pre-trained models with language modeling head on top (linear layer with weights tied to the input) for text generation and probability extraction. Due to personal computer limitations below models were used to build the application:

•	DistilGPT2 - 6-layer, 768-hidden, 12-heads, 82M parameters\
•	GPT2 (small) - 12-layer, 768-hidden, 12-heads, 117M parameters\
•	GPT2-medium - 24-layer, 1024-hidden, 16-heads, 345M parameters
