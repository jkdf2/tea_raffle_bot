Tea Raffle Bot
=============

The code for choosing winners of the 100k subscriber raffle on [/r/tea](https://www.reddit.com/r/tea).

This bot is created by [/u/taylorkline](https://www.reddit.com/user/taylorkline/).

About
-----

This bot requires `python3.6`.

After updating the appropriate global variables and renaming `praw.ini.example` over to `praw.ini` with the appropriate credentials, the following commands will get you up and running:

```
python3.6 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3.6 bot.py
```