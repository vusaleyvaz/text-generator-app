# Text Generator Application with GPT2, Huggingface Transformers, Tensorflow and Holoviz Panel

## Introduction

This is a text generator application that visualizes probability distribution for top-N tokens for the model's dictionary and allows generating texts, by having an initial prompt and using different decoding strategies.

The application was built using the open-source Panel library, which allows to build and deploy applications through jupyter notebook. The language models are taken from the Huggingface library. For the showcase, the application was built using GPT-2 models. Python, Tensorflow, and other common Python libraries were used to build the required functions.


##  GPT2
For this project, I used Huggingface pre-trained models with language modeling head on top (linear layer with weights tied to the input) for text generation and probability extraction. Due to personal computer limitations below models were used to build the application:

•	DistilGPT2 - 6-layer, 768-hidden, 12-heads, 82M parameters\
•	GPT2 (small) - 12-layer, 768-hidden, 12-heads, 117M parameters\
•	GPT2-medium - 24-layer, 1024-hidden, 16-heads, 345M parameters

## Web Application
Application is single page web application built on Panel templates:

<p align='center'>
  <a href="#"><img src='https://github.com/vusaleyvaz/text-generator-app/blob/d91e5d6ac8a9e982bd5a36a0fa23848ab2a4df86/images/application.png' width="900" height="600"></a>
</p>

### Run on localhost

After intstalling the required packages you just need to run all cells in the jupyter notebook

### Project details

All the details regarding the project (theoretical and practical part) can be found in below given document:

https://github.com/vusaleyvaz/text-generator-app/blob/279b438bf2f741cc4c64c3401f3510ca0fdd8914/documents/Master%20Thesis%20-%20Visualization%20of%20different%20decoding%20strategies.pdf

### Requirements
Below is the list of required packages that were used during building the application where version of Python is 3.8.5:\
• numpy == 1.19.2\
• bokeh == 2.4.1\
• tensorflow == 2.6.0\
• transformers == 4.11.3\
• panel == 0.12.4

Moreover, below is the list of jupyter packages:
• jupyter core     : 4.7.0\
• jupyter-notebook : 6.2.0\
• qtconsole        : 4.7.7\
• ipython          : 7.19.0\
• ipykernel        : 5.3.4\
• jupyter client   : 6.1.7\
• jupyter lab      : 2.2.6\
• nbconvert        : 6.0.7\
• ipywidgets       : 7.6.3\
• nbformat         : 5.1.2\
• traitlets        : 5.0.5
