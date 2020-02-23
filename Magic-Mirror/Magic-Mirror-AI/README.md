# AI-Smart-Mirror
Smart Mirror with a smart AI 🤖

# Setup Guide

## Magic Mirror
Download the stable version of Node.js: 
https://nodejs.org/en/

Navigate inside the MagicMirror folder
```shell
cd MagicMirror
```

Install MagicMirror dependencies
```shell
sudo npm install
```
 
Verify it starts
```shell
npm start
```
 
 
## AI
 
Make sure Ruby Java and Pyhton is installed: https://www.ruby-lang.org/en/documentation/installation/
 
 
Navigate to the AI-Smart-Mirror folder
```shell
cd Magic-Mirror-AI
```

Install ffmpeg
```
apt-get install ffmpeg
```

Use `setup.sh` to create a virtual environment and install dependencies
```shell
sudo ./setup.sh
```

Activate the virual evironment
```shell
source hhsmartmirror/bin/activate
```

Make sure MagicMirror is running, then start the AI
```shell
python bot.py
``` 
Please download missing modules within that where not installed during your python installation and might give import error apon start-up.
