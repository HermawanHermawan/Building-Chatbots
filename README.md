BRIEF HISTORY OF CONVERSATIONAL SOFTWARE

Conversational Software is not a new idea. In fact, the invention of keyboard and video screen terminal brought on the first wave of command line apps in the 1960s. To use a command line app, you ave to type instructions using a language that's very strict, but already much closer to human language than the underlying machine instructions. Around the same time, the ELIZA program was created This now famous program was able to hold a conversation by using a rule-matching engine. Despite the relatively simple code behind ELIZA, it's actually a pretty compelling conversationalist. 

PROJECT DESCRIPTION

ECHOBOT

This project aims to build up minimal version of the ELIZA chatbot. In this case, we used regular expression and machine learning to extract meaning from free-form text. The first bot built is called EchoBot, because it simply echoes back whatever we say to it. For simplicity, all the bots will receive messages in python code, and will print their responses to the screen. Building up this bots will include function definition in Python. The first will be 'respond' function taking a message as an argument and returning an appropriate response. The other is 'send_message' function keeping track of everything that is being said. It will print what the user just said, get the response by calling the first function, and then print the bots response as well. To make the conversation natural, we will create an artificial delay by importing the 'time' module. 

PERSONALITY

Creating an engaging personality is a fun and absolutely crucial part of chatbot development. It is one of the key differences compared to any other kind of software. It is therefore important to create 'chatbot personality'. If all we could do is typing precise instructions to our bot, we would actually just have a command line application, not a chatbot. Most chatbots are embedded in a messaging app that people are comfotable using to talk to their friends. We can expect that the users will want to make a bit of small talk, often before trying out any 'functionality' that they came for. To create such smalltalk, we can use a python dictionary, with user messages as the keys and responses as the values. 