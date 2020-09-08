# Health-Emergency-Chatbot

Internship Project

A Chatbot for addressing grivences related to health emergencies.

## Installation 
To run the code, you will need Rasa NLU, Rasa Core and spacy installed. You can do it by running:
`python -m pip install -U rasa_core==0.9.6 rasa_nlu[spacy]`

You will also need a spacy language model which you can download by executing:
`python -m spacy download en_core_web_md`

`python -m spacy link --force en_core_web_md en`

## How to run the code
The repo contains two notebooks:
- `Rasa_Emergency_Chatbot_Colab` -- the colab notebook for the chatbot
- `rasa_emergency_def` -- the jupyter notebook for the chatbot
