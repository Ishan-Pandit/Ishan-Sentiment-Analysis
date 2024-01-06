# Sentiment Analysis of a WhatsApp Chat

Hello! I am Ishan Pandit (rollno: 22b2141), and this repository contains my Python code for sentiment analysis of WhatsApp chats. 

The initial part of my code focuses on preprocessing exported chat data. This includes handling date-time formats and identifying message authors. I defined functions to streamline and simplify this process, ensuring less confusion while reading the code.

For the chat analysed in the code, I simply exported one of my WhatsApp chats, saved it (without media to reduce the possibility of error), and provided the file path in the code.

I used the nltk (Natural Language ToolKit) library for the sentiment analysis part of the code. The code calculates sentiment scores for each message —distinguishing between positive, negative, and neutral sentiments. This is done using a sentiment analyser function present in the nltk library. Finally, I compared the cumulative sentiment analysis scores, and thus determined the predominant emotion throughout the chat! 
