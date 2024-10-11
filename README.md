# Moonbix-bot
Python bot for Moonbix (FUNCTIONAL!)
## Recommendation before use

# Join the bot [here](https://t.me/Binance_Moonbix_bot/start?startApp=ref_1874940389&startapp=ref_1874940389&utm_medium=web_share_copy)

> [!WARNING]
> ⚠️ I strive to minimize the likelihood of bot detection, but the use of bots is prohibited in all airdrops. I cannot assure you that you won't be flagged as a bot. Proceed at your own risk. I take no responsibility for any outcomes resulting from the use of this software. This software is intended solely for educational purposes.

# 🔥🔥 MUST USE PYTHON 3.11.5 (CAPTCHA VERSION ISN'T WORK ON TERMUX)🔥🔥

## Features  
| Feature                                                     | Supported  |
|---------------------------------------------------------------|:----------------:|
| Multithreading                                                |        ✅        |
| Proxy binding to session                                      |        ✅        |
| Auto ref                                                      |        ✅        |
| Auto checkin                                                  |        ✅        |
| Auto play game                                                |        ✅        |
| Auto solve captcha                                             |        ✅        |
| Support for pyrogram .session                                 |        ✅        |
Auto get maxium points each game        |        ✅        |
## [Settings](https://github.com/BotifyBoost/moonbix-bot/blob/main/.env-example)
| Settings | Description |
|----------------------------|:-------------------------------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**      | Platform data from which to run the Telegram session (default - android)                                      |       
| **REF_LINK**               | Put your ref link here (default: my ref link)                                                                 |
| **AUTO_TASK**              | Auto do task (default: True)                                                                                  |
| **AUTO_PLAY_GAME**         | AUTO PLAY GAME (default: True)                                                                                |
| **MORE_ACCURATE_CAPTCHA_SOLVER**         | Option to use more accurate solver (it will slower) (default: False)                                                                                |
| **DELAY_EACH_ACCOUNT**         | SLEEP between each account (default: [15,25])                                                                                |
| **USE_PROXY_FROM_FILE**    | Whether to use a proxy from the bot/config/proxies.txt file (True / False)                                    |


## Quick Start 📚

To install libraries and run bot - open run.bat on Windows

## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.11.5**

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Installation
You can download the [**repository**](https://github.com/vanhbakaa/Kaia-bot/) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/BotifyBoost/Moonbix-bot.git
cd Moonbix-bot
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/moonbix-bot >>> python3 main.py --action (1/2)
# Or
~/moonbix-bot >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```
You can also use arguments for quick start, for example:
```shell
~/moonbix-bot >>> python main.py --action (1/2)
# Or
~/moonbix-bot >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```


### Contacts

Git hub (https://github.com/BotifyBoost)
Telegram [https://t.me/+yuPCMXgUMddlZjg9]
