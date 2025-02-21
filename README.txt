1️. Create a Telegram Bot
    1. Open the Telegram app (web or mobile) and log into your account.
    2. In the search bar, type BotFather and open the verified bot (with a blue checkmark ✅).
    3. Type /newbot and press Enter.
    4. BotFather will ask for:
     A name for your bot → Choose any name you like.
     A username for your bot → It must be unique and end with "bot" (e.g., MyHelperBot).
    5.Once done, BotFather will generate a Telegram Bot Token.
    6.Save this token securely—do not share it, as it allows full control of your bot.
2️. Get Your OpenAI API Key
    1.Visit the OpenAI Developer Console → https://platform.openai.com/
    2.Sign in (or create an account).
    3.Go to the API Keys section and generate a new OpenAI API key.
    4.Choose a GPT model (e.g., GPT-4o) based on your needs.
    5.OpenAI requires a paid plan, so ensure your account has credits.
3️. Connect Your Telegram Bot to OpenAI
    1.Write a Python script that:
    2.Uses the Telegram API to receive user messages.
    3.Sends these messages to OpenAI’s GPT API.
    4.Receives and returns ChatGPT’s response inside Telegram.
    5.Store your Telegram Bot Token and OpenAI API Key securely in a .env file.
    6.Run your bot, and it will start responding to user queries with AI-generated answers.
