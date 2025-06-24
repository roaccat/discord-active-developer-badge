<div align="center">
<h1>Discord Active Developer Badge Bot</h1>
<p>
      <img src="https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square" alt="JavaScript">
  		<a href="https://www.npmjs.com/package/discord.js"><img src="https://img.shields.io/npm/v/discord.js.svg" alt="DiscordJS Version"/></a>
</p>
</div>
  
## How To Use
1) Download all files and gather up on one file
2) Install NodeJS - https://nodejs.org/en/
3) Open CMD or PowerShell on file
4) Write `npm i discord.js` then press enter
5) Write `npm install` then press enter
6) Edit the `config.json` with your information
7) Write `node deploy-commands.js` then press enter
8) Finally you can run your bot. Write `node index.js` then press enter

## Console Commands
- `node deploy-commands.js` - register slash commands
- `node undeploy-commands.js` - delete all slash commands 
- `node index.js` - start the project

## Bot Commands
- Available slash commands, `/ping` & `/server` & `/user` & `/reload`

##  FAQ (Frequently Asked Questions)
### `config.json` – Configuration Guide
Here are some common questions related to the values you need to provide in your `config.json` file:
<details>
  <summary><b>How do I find my bot token?</b></summary>
  <br/>
  Go to the <a href="https://discord.com/developers/applications">Discord Developer Portal</a> and select the bot you've created. From the left-hand sidebar, click on the <b>Bot</b> section. Under the <b>Token</b> section, click <b>Reset Token</b> to generate a new token. You can only view the token <b>once</b> after generating it. If you lose it, you'll need to reset it again.<br/><br/>
  <b>⚠️ Never share your bot token with anyone.</b><br/><br/>
  <img src='https://github.com/roaccat/discord-active-developer-badge/blob/main/img/bot-token.gif' alt='Bot Token GIF'></img>
</details>
<details>
  <summary><b>What is a prefix?</b></summary>
  <br/>
  A prefix is a character or set of characters that come before a command (e.g., `!ping`, `!user`). It tells the bot you're entering a command.
</details>
<details>
  <summary><b>How do I find my client ID?</b></summary>
  <br/>
  Go to the <a href="https://discord.com/developers/applications">Discord Developer Portal</a> and select the bot you've created. From the left-hand sidebar, click on the <b>OAuth2</b> section. Under the <b>Client information</b> section you will find.<br/><br/>
  <b>⚠️ Never share your client ID with anyone.</b><br/><br/>
  <img src='https://github.com/roaccat/discord-active-developer-badge/blob/main/img/client-id.gif' alt='Client ID GIF'></img>
</details>
<details>
  <summary><b>How do I find my guild (server) ID?</b></summary>
  <br/>
  Enable Developer Mode in your Discord settings. Then, right-click your server’s name and select "Copy Server ID".<br/><br/>
  <img src='https://github.com/roaccat/discord-active-developer-badge/blob/main/img/guild-id.gif' alt='Guild ID GIF'></img>
</details>

### How do I claim Active Developer Badge?
Go to the <a href="https://discord.com/developers/active-developer">Discord Developer Portal</a> and press <b>Claim Badge</b> button.
For more information go to the <a href="https://support-dev.discord.com/hc/en-us/articles/10113997751447-Active-Developer-Badge">Discord Support Article.</a>

## License
This Discord Bot is under the [[GNU Lesser General Public License, v3.0]](https://github.com/roaccat/discord-active-developer-badge/blob/main/LICENSE).
