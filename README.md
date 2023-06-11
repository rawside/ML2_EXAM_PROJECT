# ML2 - EXAM Project 

##Introduction
---
Welcome to my Python Notebook, where I'm undertaking a study of sentiment analysis in the realm of cryptocurrency, with a particular emphasis on the social media platform Twitter.

Cryptocurrencies are known for their price volatility, which can be influenced by a wide array of factors. Among these, I'm examining the role of Twitter, a platform where discussions about cryptocurrencies are constantly happening in real time.

In this project, I'll be gathering tweets related to different cryptocurrencies using the Twitter API, and then applying sentiment analysis to this data. The aim here is to determine the underlying sentiments expressed in tweets about specific cryptocurrencies.

I plan to train my own model (on the sentiment140 dataset from Huggingface) and also leverage the OpenAI API to ascertain the sentiment of these tweets. Over a certain period, I'll amass data from Twitter and use both my model and the OpenAI API to predict the sentiment expressed in these tweets.

Furthermore, I'll create a function to track how sentiment changes over time. For this analysis, I'll only consider tweets where the sentiment predictions from my model and OpenAI coincide. This accumulated data could potentially be useful for future model training.

So, I invite you to join me on this scholarly journey that merges Python, cryptocurrencies, Twitter, and sentiment analysis. Let's explore what Twitter discussions reveal about sentiments within the crypto market!

##How to use the Notebook for the oral exam
---
This notebook is designed to be executed in Google Colab. To run the notebook, you can download it and upload it to your Google Colab environment. However, please note that you will need specific credentials for the APIs and database used in this notebook.

I have prepared a JSON file containing all the required credentials. There's an upload function for the credentials within the code. Please do not push the credentials to any public repository. If you haven't received the JSON-file via email for the review, please feel free to send me an email at pfeifsas@... and I will provide you with the necessary credentials.
