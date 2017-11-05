# Smart_Mirror
Smart Mirror with AI as well as home automation.

## Open Source

1) [MichMich MagicMirror](https://magicmirror.builders/)

### Code Requirements
The example code is in Python ([version 2.7](https://www.python.org/download/releases/2.7/) or higher will work). 

1) import speechrecognition
2) import gtts
3) import py4j
4) import python-dateutil
5) import pydub
6) import feedparser
7) import numpy

# Setup Guide

## Magic Mirror
Download the stable version of Node.js: 
https://nodejs.org/en/

Clone the latest MagicMirror code from:
https://github.com/MichMich/MagicMirror

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
 
 
Clone this repository (AI Smart Mirror)
```shell
git clone git@github.com:akshaybahadur21/Smart_Mirror.git
```

Copy the folders in `Smart_Mirror/magic_mirror` to `MagicMirror/modules`

Copy the `config.js` file in `Smart_Mirror/magic_mirror` to `MagicMirror/config`
 
## AI
 
We are using [wit.ai](https://wit.ai/) for generating intents out of the text.
You need to generate an access id using which, you can send GET requests to get intents.

## Weather

For weather we are using [darksky.net](https://darksky.net/).
You have to create your own developer account and get the API key.

## Youtube
For enabling youTube, you need to get the youTube secret Key from the Google's developer Console.
Add the key in the code.

## Maps

For map, we are using Google maps. Types of map we support right now are :
1) Normal
2) Hybrid
3) Satellite
4) Terrain

## News

For news, we use Google news and the location has been set to IN (INDIA).
You can change it according o your country to get the latest news.

## Uber

You can directly book an uber and get the arrival map using this module.
You need to get the API Key, Client Secret, Oauth Key and paste it in the code.

## Zomato

For zomato, you need to get the API key from zomato's dev site.
And paste it in the code. 
You can view the list of available restaurants in a region.
 
Navigate to the AI-Smart-Mirror folder
```shell
cd AI-Smart-Mirror
```

Make sure MagicMirror is running, then start the AI
```shell
python bot.py
```

## Setup Facial Recognition
[Refer to this guide](http://opencv-python-tutroals.readthedocs.io/en/latest/)

Install openCV with 
```shell
pip install cv2
```

Start the app
```shell
python bot.py
```

# Code shall be uploaded soon once the test phase is completed
 