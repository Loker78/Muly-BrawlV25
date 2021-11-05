# Brawl Stars v25

Experimental Brawl Stars v25 server emulator written in Python.

![ScreenShot](https://media.discordapp.net/attachments/902802229566779413/906136413165223986/Screenshot_20211105-134634.png) 

### Requirements:
- Python 3.7 or higher
- tinydb

### Running the server
In a terminal, type __`pip install tinydb`__ then run the server using __`python main.py`__

### Configuring the client app
To connect to your server, a **patched client** is required. Download this [base APK](https://drive.google.com/file/d/113L5JYuv1v1Ei0zd08-G7En_kI83Bv7y/view?usp=drivesdk#) and change the IP in `libarcade.config.so`. 

⚠️ This client is unstable and might crash sometimes. It is not recommended to use it for a production environment.
### Battles
We've enabled offline battles so you can directly press "PLAY" to start a match.

Unfortunately, the offline logic is mostly broken and some gamemodes/brawlers might crash the game or not work correctly. 
After multiple tests we've made it appears these 3 gamemodes still behave normally:
- Gem Grab
- Bounty
- Big Game

You'll find some maps we've selected for you in the events tab.

### Got any question?
Contact @Loker#6603 on Discord or open an issue.

### Important Notice
This is an experimental and incomplete server made just for fun. No database, no data saving. 
The purpose of this project is to prove that making a private server for Brawl Stars is still possible.
We won't provide further updates nor will we offer support for miss-features or other issues.
Description