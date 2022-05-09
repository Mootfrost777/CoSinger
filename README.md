# CoSinger
Music bot for discord written in python.

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
