<!-- For future improvements (last update: Oct. 20, 2021): 
ask this AI questions about how it works: https://my.replika.ai/ 
its actually insanely useful and intelligent.
Like it told me that it uses a GAN to take input of users arrays of data to learn and predict. - model that is influenced by the user and the context of the message.

-->

# Resume-Chat-Bot
The machine learning model development behind my Python AI Chatbot for answering questions related to my resume. <!-- utilizing tensorflow keras DNN and sklearn LinearSVC models as well as nltk and spacy for NLP.-->

This repo is for the CLI based version of the Chatbot. It shows the development, training, and selection process of the models and NLP pipelines. The CLI chatbot responses utilize and display the results from each of the existing models as opposed to only using the most accurate model. 

The web app repo for this project can be found at https://github.com/Iliaromanov/Resume-Chatbot-WebApp

The repo for the NLP pipeline API I built as a microservice for this project's web app utilizing the NLP pipelines developed in this repository can be found at https://github.com/Iliaromanov/nlp-pipeline-API

![Python](https://img.shields.io/badge/-Python-05122A?style=flat&logo=Python)
![Tensorflow](https://img.shields.io/badge/-Tensorflow-05122A?style=flat&logo=Tensorflow)
![Keras](https://img.shields.io/badge/-Keras-05122A?style=flat&logo=Keras)
![Scikit](https://img.shields.io/badge/Scikit_Learn-05122A?style=flat&logo=scikit-learn)
![NLTK](https://img.shields.io/badge/-NLTK-05122A?style=flat&logo=NLTK)


## Installation and Setup for CLI Usage

> `git clone https://github.com/Iliaromanov/Resume-Chat-Bot.git`

> `cd Resume-Chatbot-Model`

> `pip install -r requirements.txt`

> `python main.py`

<!--
Intents I want to use in the future but don't have the frontend for yet:

{"tag": "iliaBOT_other_options",
    "patterns": ["What other things can you tell me about?",
                 "What else can you help me with?",
                 "What are my other options?",
                 "Is there anything else you can do, besides what you've shown me?",
                 "What else can you tell me",
                 "How else can you help me",
                 "What are my other options?",
                 "Can you show me the other options",
                 "Could you show me anything else, other than what I've seen so far?",
                 "Extra other options",
                 "other options"
                ],
    "responses": ["😳 Looks like you found a feature Ilia hasn't finished building yet. For now lets just move on pretend this never happened ..."],
    "context_set": "Here are some other things I can help you with"
},

Have a quick chat with IliaBOT for an interactive way to get some insights about myself and my resume!
-->
