Creating a Telegram Bot

Let's get started! In this tutorial we'll use the Python library provided by Telegram called [python-telegram-bot](https://github.com/python-telegram-bot/).
Let's get started!

1. Fire up a command line and install the required libraries through your command line by running:
In this tutorial you'll get a Telegram Bot up and running on your local enviornment. Later you'll also learn how to deploy it to your OpenShift server.

	`pip install -r requirements.txt`
We'll use the Python library provided by Telegram called [python-telegram-bot](https://github.com/python-telegram-bot/).

2. Create or sign in to your [Telegram Account](https://web.telegram.org/)
To begin, you'll need a Telegram Access Token for your Bot.

3. Search for `@BotFather`
1. Create or sign in to your [Telegram Account](https://web.telegram.org/)

2. Search for `@BotFather`

	![Search for @BotFather](demo/botfather_conversation.png "Search for @BotFather")

4. Initialize a conversation with the `@BotFather`
3. Initialize a conversation with the `@BotFather`

	![Initialize Conversation with BotFather](demo/botfather_init.png "Initialize Conversation with BotFather")

5. Create a new bot by typing `/newbot` and follow the guided process.
4. Create a new bot by typing `/newbot` and follow the guided process.

	Congratulations, you've created your Telegram Bot :) 

6. Generate an access token which you'll need to communicate with your bot by typing `/token`
5. Generate an access token which you'll need to communicate with your bot by typing `/token`

6. Replace your Telegram access token in `telegram.py` by `YOUR TOKEN`

7. Fire up a command line and install the `python-telegram-bot` library through your command line by running:

7. Replace your Telegram access token in `telegram.py`
	`pip install python-telegram-bot`

8. Then import `telegram.py` via `import telegram` at the top of your `main.py`
9. To start your bot run `python bot.py` (stop your bot by running CTRL+Z)

9. Your Bot supports following things:
10. Your Bot supports the following inputs:
	* /start
	![/start command](demo/botfather_start.png "/start command")
	* /hello
@@ -38,12 +44,18 @@ Let's get started! In this tutorial we'll use the Python library provided by Tel
	* Echoes messages
	![Echo text](demo/botfather_echo.png "Echo text")

### Deploying your bot to OpenShift

Coming soon …

## Notes

Add `@Hello_Telegram_Bot` and send him a message to test the features in this tutorial.

Find more infos and documentation about `python-telegram-bot` at [https://github.com/python-telegram-bot/](https://github.com/python-telegram-bot/)

To send 🔊 audio, 🖼 photos, etc check out the [Telegram Bot API](https://core.telegram.org/bots/api) 🙂

### Examples by `python-telegram-bot`

Get inspired by more [Examples](https://github.com/python-telegram-bot/python-telegram-bot/tree/master/examples) here:
@@ -66,4 +78,7 @@ This example sheds some light on inline keyboards, callback queries and message

**[`inlinebot.py`](https://github.com/python-telegram-bot/python-telegram-bot/blob/master/examples/inlinebot.py)**

A basic example of an [inline bot](https://core.telegram.org/bots/inline). Don't forget to enable inline mode with [@INFOTECH_C_BotFather_bot](https://telegram.me/BotFather).
A basic example of an [inline bot](https://core.telegram.org/bots/inline). Don't forget to enable inline mode with [@INFOTECH_C_BotFather_bot](https://telegram.me/BotFather).



