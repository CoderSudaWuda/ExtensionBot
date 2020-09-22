# ExtensionBot

### Selfbots, sadly, are against the ToS of Discord. Use at your own risk.
Discord's API provides a separate type of user account dedicated to automation, called a bot account. Bot accounts can be created through the applications page, and are authenticated using a token (rather than a username and password). Unlike the normal OAuth2 flow, bot accounts have full access to all API routes without using bearer tokens, and can connect to the Real Time Gateway. Automating normal user accounts (generally called "self-bots") outside of the OAuth2/bot API is forbidden, and can result in an account termination if found.

ExtensionBot is a nifty little selfbot made with Discord.js, which can make life easier. From getting the avatar of a user to embedding messages, this bot
has it all!

## Installation
Installation is as easy as pie! However, some programs must be downloaded and added to PATH for this bot to be able to run.

- **[Git](https://git-scm.com/download)**
- **[Node.js](https://nodejs.org/en/)**

Once you have finished downloading the above and adding them to PATH, you're almost done!

- Open a Command Prompt or Powershell inside the folder you want the selfbot to be.
- Run `git clone https://github.com/CoderSudaWuda/ExtensionBot.git`
- Once that is finished, you must go to the config.json and edit it. Replace "YOUR_TOKEN_HERE" with your actual token, and replace "YOUR_PREFIX_HERE" with your desired prefix. **If you do not know how to get your token, [click here](https://www.youtube.com/watch?v=tI1lzqzLQCs) (p.s. you cannot get your token if you have 2FA enabled)**
- Run the command `npm install`, then run `npm start`.
- Your bot should be online! Tada 🎉🎉🎉
- Keep checking the console, as errors may show up.