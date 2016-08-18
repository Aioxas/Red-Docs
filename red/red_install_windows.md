---
title: Installing on Windows
sidebar: red_sidebar
permalink: /red_install_windows/
last_updated: Aug 18, 2016
---

> Disclaimer: If you modify tracked files (like .py) and then update with git, it might cause a conflict and Red won't be able to update. Modify any file at your risk.

### Software
{% include callout.html content="**Important**: Remember to do the following!<br/><br/>Select 'Add Python to path'<br/>Select 'Use Git from the Windows Command Prompt'<br/>*See the screenshots for more information*" type="info" %}
- [Install Python](https://www.python.org/downloads/). Red **needs** 3.5.0 or superior.  
![](http://i.imgur.com/dfsaVLx.png)<br/><br/>
- [Install Git](https://git-scm.com/download/win)  
![](http://i.imgur.com/guis7EE.png)  

Failure to add the above sofware to PATH like shown will result in failure of the following steps.

## Installation

* Go to the folder you want to install Red in. Don't create a separate folder for it, the installer will do it by itself.  
Right click. This is what you should see.  
![Git bash](http://i.imgur.com/32M4VPo.png)

* Open git bash and you should see a console similar to Windows' command prompt.  

![Git bash](http://i.imgur.com/IUz179P.png)

* Copy/paste this:
```
git clone -b develop --single-branch https://github.com/Twentysix26/Red-DiscordBot.git Red-DiscordBot
```

Git should now start downloading the files and put everything into a folder called "Red-DiscordBot". This will be the content of the folder:  
![mainfolderwin](https://i.imgur.com/603QQYK.png)  

* If you're interested in audio features, double click download_ffmpeg.bat

* Right click update.bat and open it as admin. This will install the requirements and will also allow you to update Red and its requirements in the future.

* Double click startRed.bat

It will ask you for a token. Make a new bot user by following the ["Creating a new bot account"](/Red-Docs/red_guide_bot_accounts/#creating-a-new-bot-account) section.  

Complete the configuration process. You'll be able to invite your bot to your server by using the invite link that's provided at boot.

## Updates

To update Red, simply run as admin the update.bat
