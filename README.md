# telegram_bot
Learning how to create a Telegram bot :D

## #1: The BotFather
Command: /newbot 
This will allow you to create a new bot,
take note of where to find the bot and the API key!

## #2: Setting up your bot
1. Search for the bot name http://t.me/(BOT_NAME)_bot 
2. Send any message to the bot
OR
1. Add the bot to an existing group chat
2. Send any message to the bot

3. Enter https://api.telegram.org/bot(TOKEN)/getUpdates
4. Retrieve the chat ID

## #3. Sending a message from the bot
1. https://api.telegram.org/bot(TOKEN)/sendMessage?chat_id=(CHAT_ID)&text=(TEXT)
