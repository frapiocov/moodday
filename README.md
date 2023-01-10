# moodDay

Bot for Cloud course project

This bot has been created using [Bot Framework](https://dev.botframework.com), it shows how to create a simple bot that accepts input from the user and echoes it back.

## Prerequisites

This sample **requires** prerequisites in order to run.

### Install Python 3.6

## Running the sample
- Run `pip install -r requirements.txt` to install all dependencies
- Run `python app.py`


## Testing the bot using Bot Framework Emulator

[Bot Framework Emulator](https://github.com/microsoft/botframework-emulator) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the Bot Framework Emulator version 4.3.0 or greater from [here](https://github.com/Microsoft/BotFramework-Emulator/releases)

### Connect to the bot using Bot Framework Emulator

- Launch Bot Framework Emulator
- Enter a Bot URL of `http://localhost:3978/api/messages`


## Deploy and execute

1. Create and enable a virtual enviroment  
`D:\user>python -m venv venv`  
`D:\user>venv\Scripts\activate.bat`

2. Install the packages using the pip install command  
`pip install botbuilder-core`  
`pip install asyncio`  
`pip install aiohttp`  
`pip install cookiecutter==1.7.0`  

3. Run the bot  
`cd moodDay`  
`pip install -r requirements.txt`  
To start the bot, run the below command  
`python app.py`

4. Open Bot Framework Emulator, enter the Bot URL that was shown in the command line appended with "/api/messages" -> 'http://localhost:3978/api/messages' and click on **Connect**.

### The MoodBot
