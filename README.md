# RASAchatbot

Built from this article 
https://towardsdatascience.com/building-a-conversational-chatbot-for-slack-using-rasa-and-python-part-1-bca5cc75d32f

##Rasa NLU
python -m pip install rasa_nlu[spacy] (https://rasa.com/docs/nlu/installation/)
##Rasa Core
python -m pip install -U rasa_core
(https://rasa.com/docs/core/installation/)
##Language Model
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en --force;

To Load conda environemnt run :
conda create --name RASAchatbot --file spec-file.txt