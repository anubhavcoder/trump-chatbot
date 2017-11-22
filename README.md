# Trump-chatbot

This is a final project for the Python class that I took on Codecademy. In this project, I created a chatbot using the Markov Chain module that Codecademy provided (link: https://github.com/Codecademy/markov_python). I tried to create a chatbot that any user could talk to whenever they wish. The most interesting part of this project was that I fed all of Trump's tweets to the Markov Chian, which then generated the sentences randomly for the chatbot. That being said, as an user, you would talk to a chatbot that ideally would talk like Trump (or at least talk like how he tweets).

# To run the chatbot

It's pretty easy!
You will need to download the zip file, unzip the file, and execute run.py on your machine. You will need to have Python 2 installed on your machine to run the chatbot.

# Files included in the zip file

a. run.py: Setting up the interface of how the chatbot will interact with you.
b. data.txt: The data (i.e., Trump's tweets) that I fed to the Markov Chain. 
c. markov_python folder
  a) cc_markov.py: The Markov Chain module that Codecademy provided. 
  b) Fetch_data.py: I used Twitter API to fetch the data and stored the data in data.txt. 
                    (I manually moved data.txt to the same folder with run.py) 
  c) raw_text.json: This is a backup file of all the tweets that I fetched in json format.
                    (The code was not included in Fetch_data.py since I didn't get to use this file in the end)
  d) README.md: Instruction for cc_markov.py.
  e) LICENSE: The license to the Markov Chain module provided by Codecademy.

# Note to the data that I fed to the chatbot

The tweets I fed to the chatbot were dated from 2016/12/1 to 2017/11/21. There were roughly 2500 tweets.

# Potential next step for the chatbot

a. Make Trump (i.e., the chatbot) smarter, and it might be done by...
a) Clean the data in data.txt: Currently the data includes many "http://" and "RT" and these words make the chatbot's sentence awkard. Remove these words might make the chatbot smarter. 
b) Fetch more tweets: I was only able to fetch about 2500 tweets each time due to the rate limit posed by Twitter API. There were still many tweets could be fed to the chatbot to make it smarter.
b. Make Markov Chain more responsive: Is it possible to make the Markov Chain module to generate sentences according to what the user inputs? If so, the chatbot might act in a more responsive manner.
