# StackOverFlow_bot
This is a dialogue chat bot which I created as a part of Natural Language Processing course by HSE at Coursera. This bot was hosted on Amazon Web Services and was peer reviewed.

The Sttackbot(as I named it) is able to:
1) answer programming-related questions (using StackOverflow dataset);
2) chit-chat and simulate dialogue on all non programming-related questions.

For answering programming-related questions, STARSAPCE EMBEDDINGS which were trained on StackOverflow dataset, were used. 

The Intent Recognition task in this bot involved predicting whether the user is asking a programming related question or a simple dialogue. 
For this binary classification problem, Logistic Regression algorithm was used. 

The  tag prediction task in the bot involved identifying the language about which the user is asking the question. This task of Multi Class Classification was acheived using OneVsRestClassifier wrapper over LogisticRegression

For a chit-chat mode we will use a pre-trained neural network engine available from ChatterBot.

The screen shots for the bot are attacjed below.

![alt text](https://github.com/gmt20/StackOverFlow_bot/blob/master/Screenshot_20190710-121348.png)
![alt text](https://github.com/gmt20/StackOverFlow_bot/blob/master/Screenshot_20190710-121444.png)


