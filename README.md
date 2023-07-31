### ChatBot SYNC INTERN
This project involves building a chatbot using natural language processing (NLP) techniques and a neural network model. The chatbot is designed to understand natural language input from users and provide appropriate responses based on the intent of the input. The project involves preprocessing the input text, training a neural network model, and using a JSON file to map intents to appropriate responses. The end result is a chatbot that can engage in natural language conversations with users.


### Libraries Used
1. nltk
2. random
3. json
4. pickle
5. numpy
6. tensorflow


### Files
1. chatbot_SYNC_INTERN: Main file contains building the model and training it and building the chatbot app
2. chatbot_data: Json file for kaggle dataset ' https://www.kaggle.com/datasets/niraliivaghani/chatbot-dataset'
3. classes.pkl: A file containing a list of strings representing the intents of the chatbot.
4. words.pkl: A file containing a list of strings representing the words that the chatbot has been trained on.
5. model.h5: A trained neural network model file saved in HDF5 format. The model takes a user's message as input and predicts the intent of the message as output.
