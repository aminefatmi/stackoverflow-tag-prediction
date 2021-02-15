# stackoverflow-tag-prediction
The aim of this project is to predict tags from stackoveflow. The model will take a question as input and return tags.
The dataset was extracted from StackExchange explorer using SQL queries.
https://data.stackexchange.com/stackoverflow/query/new

## Queries_from_stackexchange explorer:
"QueryResults1.xlsx"
"QueryResults2.xlsx"
"QueryResults3.xlsx"
"QueryResults4.xlsx"
"QueryResults5.xlsx"

## Notebooks_v1 (First Commit):
"PStackoverflow_01_eda_text_preproc.ipynb"
"PStackoverflow_02_code.ipynb"

## Notebooks_v2 (Model improvement):
reason for update: additional text preprocessing to improve the results of the supervised algorithm.
"PStackoverflow_01_eda_text_preproc_improved.ipynb"
"PStackoverflow_02_code_improved.ipynb"

## Slides:
"PStackoverflow_03_slides.ppt"

## Report:
"PStackoverflow_04_report.doc"

## App using Flask/Heroku: 
https://github.com/aminefatmi/stackoverflow-app-heroku  --> code
https://stackoverflow-app-heroku.herokuapp.com/  --> app interface

##App using Streamlit:
https://github.com/aminefatmi/stackoverflow-app-heroku-streamlit  --> code
https://share.streamlit.io/aminefatmi/stackoverflow-app-heroku-streamlit/app.py   --> app interface
