# ~~Yet Another~~ GitAlertBot

## Inspired From [Alone Dev](https://github.com/New-Dev3/GitGram-Bot/)

## Run Bot: 
### Local Host

* Git Clone Repo :
- For Telethon Version : `git clone https://github.com/TeamAlinaX/GitGramAlertBot`
- For Pyrogram Version : `git clone https://github.com/TeamAlinaX/GitGramAlertBot -b pyrogram`
* Make `local.env` File With the Values As Shown Below : 
```
API_ID=12222
API_HASH="API_HASH"
BOT_TOKEN="BOT_TOKEN"
HOST="http://127.0.0.1"
PORT=8000
```
* Now Just Run `python3 git_alert_core.py`
* Now Navigate To Url : `http://127.0.0.1:8080/ghook/<chat-id>` (replace <chat-id> with the chat where you want alerts to be sent)
* Go to Your Repo And Set The Webhook Url & Make Sure To Set It To Json. The Bot Should Sent Alerts Now.
* Happy Gitting :)

### Heroku
* Choose Your Fav Version And Click On Deploy Button
* Fill In The Values 
* Turn On Dyno
* Now Navigate To Url : `https://<heroku-app-name>.herokuapp.com/ghook/<chat-id>` (replace <chat-id> with the chat where you want alerts to be sent and <heroku-app-name> to your heroku app name)
* Go to Your Repo And Set The Webhook Url & Make Sure To Set It To Json. The Bot Should Sent Alerts Now.
* Happy Gitting :)
#### Telethon Version 

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TeamAlinaX/GitGramAlertBot)

#### Pyrogram
[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TeamAlinaX/GitGramAlertBot/blob/pyrogram)
