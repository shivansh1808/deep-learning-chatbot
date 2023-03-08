Setup
------
Open up your terminal, and type: 
1. ```$ git clone --recursive https://github.com/mayli10/deep-learning-chatbot```
2. ```$ cd deep-learning-chatbot``` 
3. ```$ python3 hello_chatbot.py``` This will show questions/comments and its corresponding replies.

If you would like to talk to the chatbot live, then navigate out of the deep-learning-chatbot folder, and clone sentdex's helper utilities repository in a new folder.

4. ```$ git clone --branch v0.1 --recursive https://github.com/daniel-kukiela/nmt-chatbot.git```
5. We will now use the inference utility. In your terminal, type: ```$ python3 inference.py < hello_chatbot.py```
