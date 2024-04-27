# OnlineDiscordBot

Bot for displaying the online status of your SCP: EVENT CLASSIFIED servers.

To use it you need to specify your server data in config.json file.

## Config fields:

* **servers** – an array of servers whose online you want to display;

* **bot_token** – token of your discord-bot, you can get it [here](https://discord.com/developers/applications);

* **server_ip** – address of your server;

* **server_query_port** – query port of your server for receiving data via UDP protocol. It can be different from the port of your server.


### If you have one server, the structure of the array will look as follows:
```yaml
"servers": [
    {
      "bot_token": "token",
      "server_ip": "ipv4",
      "server_query_port": 20685
    }
],
```

## Requirements:

* Python3;
* disnake library;
* python-a2s library.

> ```pip install disnake```

> ```pip install python-a2s```
