# File-sharing-Bot

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg" width ="250">
  </a>
 <br>
</p>


Telegram Bot to store Posts and Documents and it can Access by Special Links.

### Features
- Fully customisable.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/users - view bot statistics

/broadcast - broadcast any messages to bot users

/stats - checking your bot uptime
```

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `APP_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `DATABASE_URL` Your mongo db url
* `DATABASE_NAME` Your mongo db session name
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `PROTECT_CONTENT` Optional: True if you need to prevent files from forwarding
