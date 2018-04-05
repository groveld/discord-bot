# discordjs-bot

A General Purpose Node.js Discord Bot.

This is my personal bot code, and though I put it online with this nice readme for you to install and use it, I can't cater to other people's requests or desires. I update this when I feel like it with the features I want and I make breaking changes without consideration for other people's installations.

[Discord Server](https://discord.gg/2dV4xRN)
[Invite discordjs-bot](https://discordapp.com/oauth2/authorize?&client_id=306182346929995778&scope=bot&permissions=2146958583)

## Features

- [ ] `Auto-ban` user if @mention more than 25 users in a single message.
- [ ] `Polls` Bot posts some useful server statistics.
- [ ] `Music player` Bot posts some useful server statistics.

- [ ] `!ping` Bot posts some useful server statistics.
- [ ] `!eval` Bot posts some useful server statistics.
- [ ] `!help` Bot posts some useful server statistics.
- [ ] `!invite` Bot posts some useful server statistics.
- [ ] `!clean` Bot posts some useful server statistics.
- [ ] `!stats` Bot posts some useful server statistics.
- [ ] `!cat` bot posts a random cat picture
- [ ] `!dog` bot posts a random dog picture

## Requirements

- `git` command line ([Windows](https://git-scm.com/download/win)|[Linux](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)|[MacOS](https://git-scm.com/download/mac)) installed
- `node` [Version 8.4.0 or higher](https://nodejs.org)

## Downloading

In a command prompt in your projects folder (wherever that may be) run the following:

`git clone https://github.com/eslachance/evie.selfbot.git`

Once finished:

- Create a webhook in a channel where you want logs to appear (Channel Settings, Webhooks) and grab its ID and token.
- In the folder from where you ran the git command, run `cd evie.selfbot` and then run `npm install`
- Rename `config.json.example` to `config.json`
- Edit `config.json` and enter your token and other details as indicated. It should look like this afterwards:

## Installation

**Node 7.0.0 or newer is required.**

When running a bot using discordjs-bot, make sure to run Node with the `--harmony` flag. Examples:

- `node --harmony ./app.js`
- `pm2 start --name "discordjs-bot" --node-args="--harmony" ./sharder.js`

No version of Node older than 7.0.0 supports `async`/`await`, although you can compile it down to ES6 or ES5 with the [fast-async](https://www.npmjs.com/package/fast-async) Babel plugin. You must do this for your code and the framework's manually if you wish to use discordjs-bot on older Node versions.

## Starting the selfbot

To start the selfbot, in the command prompt, run the following command:
`node app.js`

> If at any point it says "cannot find module X" just run `npm install X` and try again.
