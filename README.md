# The Tameshk Discord server BOT(Classic Version)
## This project is no longer maintained(Version 3 is under development and You can find its repository [here](https://github.com/TameshkTeam/Discord-bot/))
***
## What is this
We used this bot for manage our server.Made by @seyedmm and @nimagp
## Requirements
- Python 3
- [py-cord](https://github.com/Pycord-Development/pycord)(recommended) or [discord.py](https://github.com/Rapptz/discord.py)
- PIP or [Poetry](https://python-poetry.org/)
## Install
1. Install python from [official site](https://python.org/)
2. Clone this project
3. Install required packages using pip
```bash
pip3 install -r requirements.txt 
```
4. set your [Discord bot token](https://www.writebots.com/discord-bot-token/) using this command before run or use [this package](https://pypi.org/project/python-dotenv/) to set token in a file(.env)
``` bash
Linux and mac:
export DISCORD_TOKEN=Your Token
Windows:
set DISCORD_TOKEN=Your Token
```
For use youtube turn command you should set the turns as Iranian weekdays name.For example:
``` bash
Linux and mac:
export "سه شنبه"=Mention of user(in bots format)
Windows:
set "سه شنبه"=Mention of user(in bots format)
```
**Some minor configurations are in the code itself, such as the channels ID and admins ID list, and you need to change them as well.**

5. Run bot with this command
``` bash
python3 bot/main.py
```
