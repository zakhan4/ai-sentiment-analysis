# sentiment-analysis
AI based Context and Sentiment Analysis for Messaging

# Prerequisites
Create a folder named 'word_vectors' inside the root folder, and downlad in this folder the embeddings from these two links:
- [Sentiment Specific word embeddings (SSWE)](http://ir.hit.edu.cn/~dytang/paper/sswe/embedding-results.zip)
- [GLoVe](https://nlp.stanford.edu/projects/glove/)

# To run
- DNN.ipynb: Used to train models and then save them inside 'results' folder
- TelegramClient.ipynb: Connects to the Telegram application, reads the chats and predicts the sentiment using the trained model and replies with the sentiment score
