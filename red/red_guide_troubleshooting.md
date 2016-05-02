---
title: General problems
sidebar: red_sidebar
permalink: /red_guide_troubleshooting/
---

Take a moment to read the error you're getting and see if the solution is already in this page.  I'm not reporting the full error here, only a line, so read carefully.

## Installation issues  

![](https://cdn.discordapp.com/attachments/133049553984159745/146030943642058752/unknown.png)  
Upgrade discord.py using:

```
pip3 install --upgrade git+https://github.com/Rapptz/discord.py@5fa715c35033c4fd5438649a03f4d2835e7a7f06
```

![](https://cdn.discordapp.com/attachments/133049553984159745/159323163157594113/20160315153125288.png)

Upgrade discord.py using:

```
pip3 install --upgrade git+https://github.com/Rapptz/discord.py@5fa715c35033c4fd5438649a03f4d2835e7a7f06
```

_If upgrading does not work, `pip or pip3 uninstall discord.py` and try again._

![](https://cdn.discordapp.com/attachments/133049553984159745/146034256890691584/unknown.png)  
You're missing some files. [Read and follow the instructions for cogs.audio](/Red-Docs/red_win_requirements/#python-libraries). These files need to be in the main Red-DiscordBot folder:  
![](https://cdn.discordapp.com/attachments/133049553984159745/146068865208680458/unknown.png)  

`Red is working but there are 0 cogs loaded`

Your current directory must the bot's root folder (where red.py is). Run it from there.

`ImportError: No module named 'discord'`

Your discord.py wasn't installed. Make sure you install with a command prompt and admin rights.

`SyntaxError: invalid syntax`

Your python is inferior to 3.5.0. Red needs at least 3.5.0 32bit to run. Install it.  
If you already did you might have two different versions of python and the older one is the default.

`filter:a`
Uninstall and Reinstall FFMPEG
For Linux users: `sudo apt-get purge ffmpeg && sudo apt-get install ffmpeg`

## Configuration issues

> Red is not responding to my commands

Red needs a separate account. Create a new one, don't use yours.

##Other issues
`BlockingIOError: [WinError10035] A non-blocking socket operation could not be completed immediately`

It's most likely the connection on your end. Get a stable connection (not wifi) and restart the bot. It fixes this problem 99% of the time.

`I keep getting an entries error.`

Upgrade discord.py using:

```
pip3 install --upgrade git+https://github.com/Rapptz/discord.py@5fa715c35033c4fd5438649a03f4d2835e7a7f06
```

_If upgrading does not work, `pip or pip3 uninstall discord.py` and try again._


>Why is Red spamming streamalerts?

It could be the streamer at fault or the Twitch API freaking out.

>How do I submit my own cog?

To submit your cogs you can follow [this guide](/Red-Docs/red_cog_how_to_publish/)

>Can I submit my own trivia list?

Of course! Feel free to send it to us or the Trivia "issue" on our github.

***

**If you reached the end of this list and your problem is not here, [head into #support](https://discord.gg/0k4npTwMvTpv9wrh) to get some help.**