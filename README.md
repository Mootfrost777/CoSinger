# CoSinger
Music bot for discord written in python.

# Commands list
```help``` - Shows list of available comands. <br/>
```join``` - Enters current voice channel. <br/>
```summon``` - Moves bot to the current voice channel. If not yet connected, connects to it. <br/>
```leave``` - Leaves current voice channel and clears queue. <br/>
```vol <value>``` - Ajusts the playback volume. <br/>
```now``` - Shows the current track. <br/>
```pause``` - Pauses song playback. <br/>
```resume``` - Continues playing the song. <br/>
```stop``` - Stops playback and clears the queue. <br/>
```skip``` - Vite to skip the song. It takes three votes to pass. <br/>
```megaskip``` - Experemental command. Does not works yet. Skip for admins. <br/>
```queue``` - Shows the playback queue. You can choose one of the pages, each can have up to 10 items. <br/>
```shuffle``` - Shuffles the queue. <br/>
```remove <id>``` - Removes a track from the queue by the entered number. <br/>
```loop``` - Turns on repeat of the current track. !!!WARNING. IT CAN CRASH THE BOT!!! Write again to remove the loop.<br/>
```play <querry>``` - Starts playback. All tracks in the queue will be played. The command allows you to search for tracks by name or by link.

# Installation
Install python3: <br/>
Windows: https://www.python.org/downloads/. <br/>
Linux: install it using your favorite package manager in your favorite OS.

Install dependencies:
```
pip install discord
pip install yt-dlp
pip install PyNaCl
```

You also need to install ffmpeg: <br/>
Windows: https://ffmpeg.org/download.html#build-windows. Just copy all .exe files to project directory. <br/>
Linux: Use your favorite package manager(ex. ```sudo apt install ffmpeg```) <br/>

Then create new bot in https://discord.com/developers/applications and paste token to config file.

# config.py
```
token = "<token>"
```

# Run 
```
python3 main.py
```
