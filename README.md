
# Twitch bot  
[![Run on Repl.it](https://repl.it/badge/github/whatsinmyopsec/twitchbot)](https://repl.it/github/whatsinmyopsec/twitchbot)  
<img src="https://badges.pufler.dev/visits/whatsinmyopsec/twitchbot">  
  
  This is a Twitch bot for [twitch.tvbeginbot](https://twitch.tv/beginbot). If you have any Questions regarding this Project feel free to ask.
  You found a Bug? Please create an Issue.
  
---  

Little guide on how to make it work.

1. Run this command `cp .env.example .env` or by simple rename that `.env.example` to `.env`
  
  2. Go to [Discord Developers](https://discord.com/developers/applications) and open / create your Bot Application.

3. Copy from your Bot that Token and paste it into the "**Password**" variable.

### Example:
```md  
USERNAME="Botname"  
PASSWORD="NDgyMjM0ODU1MzQygG1xAM1Mzcw.W37ENQ.SxEyK0451hK-lMaYDT-wEHdc"  
CHANNEL0="Welcome"  
CHANNEL1="offtopic"
```  
  
4. Make sure to install **npm** with these Commands:
```bash
npm i
npm run build
```

### Gratz!
Your Bot is now ready to run.
