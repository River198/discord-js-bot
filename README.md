# 🤖 About Me

![Strange Bot](https://i.imgur.com/nFrS5wC.png)

> An awesome multipurpose discord bot built using [discord.js v13](https://discord.js.org) with support for slash commands and context menus

> Demo Bot: [Invite Here](https://discord.com/oauth2/authorize?client\_id=752922609733337190\&permissions=397602323830\&scope=bot%20applications.commands)
>
> Support Server: [Join Here](https://discord.gg/fE75UShbqB)
>
> Documentation URL: [Visit Here](https://docs.strangebot.xyz)

### Prerequisites

* [Node.js](https://nodejs.org/en/) v16.6.0 or higher
* [Git](https://git-scm.com/downloads)
* [MongoDB](https://www.mongodb.com)

![](https://imgur.com/GUTpd5g)

### Getting Started

* Open the terminal and run the following commands

```
git clone https://github.com/saiteja-madha/discord-js-bot.git
cd discord-js-bot
npm install
```

* Wait for all the dependencies to be installed
* Rename `.env.example` to `.env` and fill the values
* Optionally edit `config.js`
* Type `npm run start` to start the bot

### Setting up MongoDB

* [MongoDB](https://mongodb.com/)

* Go to sign up and sign up with any of the plugins or with a username and password / If you already have an account then use that one

* After signing up you will see a clusters screen you will need to press connect, once pressing connect you will need to connect with MongoDB Compass*

Once you have gotten to the download screen you need to copy the 

```
mongodb+srv://<yourUsername>:<YourPassword>@cluster0.kqyih.mongodb.net/test
```
(This is your string URI what you will paste into your config file,  make sure to modify the username and password to whatever you set it as and DO NOT SHARE - This link would enable anyone to get data from youur bot)

 * Replit: You will need to add the Replits or your servers IP to the whitelist in the Network Access section of MongoDB, to get the IP address of the Replit go to the shell and paste this, `dig +short myip.opendns.com @resolver1.opendns.com`

Once you have gotten that IP go to the network tab of MongoDB and add it to the whitelist, and then restart the bot (make sure the MongoDB URL is in the config file)! 
MongoDB

* Server: You will need to go to your hosting providers dashboard and get your server's IP - Once you have done this go back to your MongoDB network access and add that IP!

If you need any additional help, make sure to read our guides [here](docs/additional/installation.md)

![](https://imgur.com/YdjBz2q)
### Features

Strange is a feature-rich discord bot with new features constantly being updated! Current features include

* **Auto-Moderation**: Power auto-moderation to keep your discord server clean
* **Powerful Moderation with Logging**: Moderate and log every action you take
* **Image Manipulation**: Have fun with various image `filters` and `generators`
* **Economy & XP System**: Engage user interaction with the economy and Levelling system
* **Invite Tracking**: Best invite tracking with configurable invite ranks
* **Ticketing**: Support for creating multiple `ticket` channels
* **Reaction Roles**: Support for creation of multiple custom reaction roles
* **Greeting**: Highly Customizable welcome and farewell embeds

### Categories

Strange has an extensive list of all useful commands (**more than 100**) which are categorized as follows

* **Automod**: `antighostping`, `antiinvites`, `antilinks`, `antiscam`, `maxlines`, `maxmentions`, ...
* **Admin**: `welcome`, `farewell`, `reaction-roles`, ...
* **Economy**: `daily`, `gamble`, `deposit`, `withdraw`, `transfer`, ...
* **Fun**: `cat`, `doc`, `flipcoin`, `fliptext`, ...
* **Information**: `avatar`, `roleinfo`, `channelinfo`, `guildinfo`, `profile`, ...
* **Invites**: `inviter`, `invites`, `invitesimport`, `invitecodes`, ...
* **Moderation**: `warn`, `kick`, `softban`, `ban`, `mute`, `unmute`, ...
* **Music**: `play`, `pause`, `resume`, `stop`, `skip`, `queue`, `np`, ...
* **Social**: `reputation list,` `give reputation,` ...
* **Ticket**: setup, close, log, ...
* **Utility**: `proxies`, `translation`, `weather`, `covid`, ...

A complete list of commands can be found in the [documentation](docs/commands/)

![](https://imgur.com/CUFT3ir)
### 🤝 Contributing

* Special thanks to [@Androzz](https://github.com/Androz2091/AtlantaBot) for the [dashboard](https://github.com/Androz2091/AtlantaBot) and his other cool discord bot projects
* Feel free to [Fork](https://github.com/saiteja-madha/discord-js-bot/fork) this repository, create a feature branch and submit a pull request
* You can check all the planned features [here](https://github.com/saiteja-madha/discord-js-bot/projects) or make a request for one at our discord
