1️⃣ Create a Telegram Bot
Open the Telegram app (web or mobile) and log into your account.
In the search bar, type BotFather and open the verified bot (with a blue checkmark ✅).
Type /newbot and press Enter.
BotFather will ask for:
A name for your bot → Choose any name you like.
A username for your bot → It must be unique and end with "bot" (e.g., MyHelperBot).
Once done, BotFather will generate a Telegram Bot Token.
Save this token securely—do not share it, as it allows full control of your bot.
2️⃣ Get Your OpenAI API Key
Visit the OpenAI Developer Console → https://platform.openai.com/
Sign in (or create an account).
Go to the API Keys section and generate a new OpenAI API key.
Choose a GPT model (e.g., GPT-4o) based on your needs.
OpenAI requires a paid plan, so ensure your account has credits.
3️⃣ Connect Your Telegram Bot to OpenAI
Write a Python script that:
Uses the Telegram API to receive user messages.
Sends these messages to OpenAI’s GPT API.
Receives and returns ChatGPT’s response inside Telegram.
Store your Telegram Bot Token and OpenAI API Key securely in a .env file.
Run your bot, and it will start responding to user queries with AI-generated answers.
