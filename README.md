## Project overview

I've designed this project for slack bot mission at stardance . 
It can gives you some jokes ,and cats' facts!

## Slash commands

/none-bot-ping - Check bot latency
/none-bot-help - Show available commands
/none-bot-catfact - Get a cat fact
/none-bot-joke - Get a random joke

## Screenshots

<img width="1917" height="920" alt="Screenshot 2026-10-29 114159" src="https://github.com/user-attachments/assets/80cf0ccb-d3c4-43e1-8e32-eafa400708ab" />

<img width="1568" height="902" alt="Screenshot 2026-10-28 131403" src="https://github.com/user-attachments/assets/a89066bf-830b-48b7-a6f4-f6c9ed1e1a1b" />


## Required Permissions / Scopes

- commands — Required for Slack slash commands.
- connections:write — Required for the App-Level Token used by Socket Mode.
- SLACK_BOT_TOKEN — The bot's authentication token.
- SLACK_APP_TOKEN — The token used to establish the Socket Mode connection.
- Socket Mode must be enabled in your Slack app settings.

## Self-Hosting
 
The commands to get started are:
1.git clone https://github.com/MahmoudMohamed99-AI/None_bot.git
cd None_bot
npm install
2.Create a .env file in the project directory and add your Slack credentials:
SLACK_BOT_TOKEN=your_bot_token
SLACK_APP_TOKEN=your_app_token
2.Enable Socket Mode in your Slack app settings, configure the required scopes, and install the app in your workspace. Then start the bot:
node index.js


If the setup succeeds, the terminal should display:
bot is running!
