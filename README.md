# telegram-bot-using-rasa
This link is used for integrate the telegram bot, which name is ngrok
link : https://ngrok.com/download
Step 1 : Download Zip file and Unzip install the .exe file
Step 2 : Enter "ngrok http 5005" inside the .exe 
Step 3 : Open the telegram app and create a /newbot and api key
Step 4 : Have to put on that api key and bot name in credentials.yml at telegram section like,

telegram:
  access_token: "api key"
  verify: "bot name"
  webhook_url: "ngroksitelink/webhooks/telegram/webhook"
