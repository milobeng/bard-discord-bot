# [Bard](https://bard.google.com) on [Discord](https://discord.com/) <img src="https://www.gstatic.com/lamda/images/favicon_v1_150160cddff7f294ce30.svg" width="35px" />
A discord.js bot with **Google's Bard** integrated 

> This project is made possible by [PawanOsman's GoogleBard library](https://github.com/PawanOsman/GoogleBard)

## About
- Supports reply by `Message Content` or `Interaction Reply`
- Uses `discord.js@v13` (not LTS)
- Supports continuous conversation (DM only)
- Easy to setup (need an access to Bard)

## How to setup
**Grab cookie**
1. Visit [bard.google.com](https://bard.google.com) 
2. Press F12 (open developer console)
3. Go to Application → Cookies → `__Secure-1PSID`. Copy the value of that cookie.

**Setup the bot**
1. Edit [`config.js`](/config.js), replace `COOKIE` with the cookie you've just copied & `TOKEN` with your Discord bot's token
2. Run the following commands to start the bot
```sh
$ npm install
$ npm start
```

**Ways to use**
- Use `!ask <YOUR_QUESTION>` to ask a question (in a server/guild)
- DM the bot with your question (for continuous conversation)

## 

