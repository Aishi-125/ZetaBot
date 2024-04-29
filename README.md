# NLP-Based-Chatbot
Prerequisites:

The following libraries are needed to be installed:-
1. Keras
2. NLTK
You have to download the following resources using nltk -['punkt','omw-1.4','wordnet']
3. googletrans
4. gTTS
5. Playsound
About:

A NLP based chatbot that is used to answer a specific question within its scope. This Bot is capable of communicating in Telugu,Hindi and English languages.
The model is trained to find patterns in inputs and match them to the ones in database and generate accurate responses. This is acheived with the help of Tensorflow -Keras neural networks API.
It uses NLTK library for lemmataization of input data. It also uses pickle and numpy modules for data pre-processing activities.
The output of this model is generated by using googletranslator module of python which is very famous and supports many languages.
Finally it uses Google-text-to-speech API to output the answer to the user query.
I have used sklearn for splitting data into training and test. The main purpose of doing this was to facilitate during accuracy calculation. 
After training the model gave a training accuracy of 93.62% and test accuracy of 50%. This is not a great test accuracy.
There are two reasons why test accuracy is low:
    1. The dataset is of limited size more data can be added which may improve the accuracy further.
    2. It is a model implemented using Multi-Layer perceptron but the data set was preprocessed using NLTK. Using RNN over MLP might increase the accuracy further.
