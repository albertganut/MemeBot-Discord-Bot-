MemeBot Discord Bot

MemeBot is a Discord bot that responds to specific commands with fun content. It was built using Python and the discord.py library, and fetches memes from Reddit using the Meme API.

Features: 
- Responds to the $meme command with a random meme from Reddit
- Responds to $lionel with $messi as a fun easter egg
  
Setup Instructions:
- Requirements
- Python 3.7+
- A Discord bot token (see below)
- discord.py
- requests

Installation: 
- Clone this repository:
- git clone https://github.com/your-username/MemeBot-Discord-Bot.git
- cd MemeBot-Discord-Bot
- Install dependencies: 
  - pip install discord requests
- Create a bot and get your token:
  - Go to the Discord Developer Portal
  - Click "New Application", give it a name, and click "Create"
  - In the sidebar, go to "Bot" and click "Add Bot"
  - Under the bot settings, click "Copy" to copy your bot token
  - Important: Keep your token private!
  - Paste your token into bot.py.
- Invite the bot to your server:
  - In the Developer Portal, go to "OAuth2" > "URL Generator"
  - Under "Scopes", check "bot"
  - Under "Bot Permission", check "Send Messages"
  - Copy the generated URL, open it in your browser, and invite the bot to your server
- Run the bot in terminal:
  - python3 bot.py
- Example Commands:
  - $meme → Bot replies with a random meme from Reddit
  - $lionel → Bot replies with $messi

Credits:
- This bot was created by following a tutorial from codedex.io.
