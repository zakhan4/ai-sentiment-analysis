# sentiment-analysis
AI based Context and Sentiment Analysis for Messaging

## Prerequisites
- Create a Telegram Developer App by using this guide https://core.telegram.org/api/obtaining_api_id
- Add the values for AppId, AppHash, Usernamem, and PhoneNumber in TelegramClient.ipynb

## To train the model
- TrainModel.ipynb: Used to train models and then save them inside 'results' folder
- To train model on different datasets: you can change the value of 'Data' variable, and can select any one value from these:
  1. formspring
  2. wiki
  3. twitter
  4. sentiment140
  
  By default training is done on Wikipedia datasets

## To run the Project
- TelegramClient.ipynb: Connects to the Telegram application, reads the chats and predicts the sentiment using the trained model
- Run and authenticate with the your user and telegram app info
- To find out the sentiment score, send "\<score\>" message in telegram
