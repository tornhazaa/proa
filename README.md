[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/TheMaestro0/Protection-bot.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/TheMaestro0/Protection-bot/context:javascript)
# Protection bot

## Requirements
* Discord bot token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
* Node.js v12.0.0 or newer

## Get Started
```
git clone https://github.com/TheMaestro0/Protection-bot.git
cd Protection-bot
npm install
```

## Configuration
Copy or Rename config.json.example to config.json and fill out the values:
```json
{
  "token": "DISCORD_BOT_TOKEN",
  "owners": ["YOUR_ACCOUNT_ID"]
}
```
## Feeds

* The bot 24/7 in offline mode. You can dm him by typing: "here" for chack if the bot really connected to discord API
* Add only your onwers ID's to config file. anyone not in the list the bot will remove admin role from him
* Anyone (NOT_OWNERS) trying to add administrator permission to any role. the bot will reset it to default permissions.
## License

The code in this repository is licensed under the [Apache-2.0](https://github.com/TheMaestro0/Protection-bot/blob/master/LICENSE) License by GitHub.

