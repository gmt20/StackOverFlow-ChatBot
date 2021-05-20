# StackOverFlow_bot
This is a dialogue chat bot which I created as a part of Natural Language Processing course by HSE at Coursera. This bot was hosted on Amazon Web Services and was peer reviewed.


The Sttackbot is able to:
1) find the relevant answer thread to programming-related questions (using StackOverflow dataset);
2) chit-chat and simulate dialogue on all non programming-related questions.


The Intent Recognition task in this bot involved predicting whether the user is asking a programming related question or a simple dialogue. For this binary classification problem, Logistic Regression algorithm was used.
Once the intent is known, the next task is to find the programming language  about which the user is asking the question. This task of Multi Class Classification was acheived using OneVsRestClassifier wrapper over LogisticRegression.
For finding the relevant answer thread to programming-related question, the text of existing threads of related langauge were ranked for similarity with the user question text. For converting question text to vector form we used STARSAPCE EMBEDDINGS which were trained on StackOverflow dataset.
 
For the chit-chat mode we used a pre-trained neural network engine available from ChatterBot.



The screen shots for the bot are attached below.

![alt text](https://github.com/gmt20/StackOverFlow_bot/blob/master/Screenshot_20190710-121348.png)
![alt text](https://github.com/gmt20/StackOverFlow_bot/blob/master/Screenshot_20190710-121444.png)


