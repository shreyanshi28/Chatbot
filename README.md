# Chatbot
## Project Description
The chatbot uses Yahoo Question and Answers dataset. The final.ipynb file does basic preprocessing on the dataset, shortens it and then it later converts .csv file into .txt file.
After, that I defined basic preprocessing functions for data entered by user with help of NLP techniques. I used cosine similarity to generate results. 
The sentences are vectorized and a loop runs comparing the cosine similarity of user entered sentence to the one present in .txt file. 
The sentence with most likelihood is presented as an answer. Few responses are hard coded to provide a personal touch. You can run the chatbot in Jupyter notebook itself using this file.
The app.ipynb file uses the flask framework to build an interface for chatbot. The template folder has the required html file. I used similar steps as in final.ipynb file and made use of final.txt file for corpus.
The app.ipynb file allows you to run chatbot on a local server with a well defined interface.


