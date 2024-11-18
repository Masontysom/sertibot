# Sirtibot
AI-Powered Automatic Question Paper Generator
need python version == Python 3.8.6

In the evolving educational landscape, the need for efficient and streamlined processes has never been greater. Sirtibot is an innovative solution designed to automate the generation of question papers using advanced artificial intelligence and Django Python. This tool is crafted to handle various aspects of question paper creation, MCQ GENERATION using logic for preprocessing text, extracting keywords, generating summaries, and generating MCQs from the processed text or .txt file, Question Generation using openai-api,formatting and generating Question paper PDF and formatting to create thoughtful, diverse and impeccably balanced question papers.


Welcome to Sirtibot, your indispensable partner in crafting thoughtful, diverse, and impeccably balanced question papers.

To run the file user should run the folling pip commands in the command prompt : 
```
pip install django
pip install nltk
pip install transformers
pip install openai
pip install flashtext
pip install Pywsd
pip install summarizer
pip install fpdf
pip install openpyxl
python -m spacy download en
pip install git+https://github.com/boudinfl/pke.git
pip install torch
pip install bert-extractive-summarizer
```
AI-Driven MCQ Generation: Utilizes cutting-edge natural language processing (NLP) techniques to preprocess text, extract keywords, generate summaries, and create multiple-choice questions (MCQs) from the processed text.

Question : openai, Api is used in it.

After all the pip are installed last step :

Go to the folder where the manage.py file is seen usualy on the first page and open cmd their then run 
```
py manage.py runserver
```

It will take some time for nltk to download and pwd so be patient.


(Optional)if want virtual Environment :
  ```
  py -m venv venv
  ```
  The name of the virtual environment is your choice my name is venv
  
  
  Then we have to activate it by the command:
  ```
  venv\Scripts\activate
  ```
  to run the file run all the ** pip commands ** in the virtual Environment 
  done then manage.py command and set to go.


Change the api to get the question to be generated, dashboard/view.py line 385 and setting line 41
https://github.com/Masontysom/sirtibot/blob/297df97261c52a3540a0ffdc3682af0fee3da7cb/dashboard/views.py#L384
https://github.com/Masontysom/sirtibot/blob/297df97261c52a3540a0ffdc3682af0fee3da7cb/sertibot/settings.py#L41

(error)



if any error in data base :
```
python manage.py migrate
```

