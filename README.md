# RocketGoBot
A python bot that listens to GoCD and posts relevant messages to a RocketChat (https://rocket.chat) incoming integration webhook

### Requirements
* Python :)
* You must have the gocd-websocket-notifier plugin installed on your Go server - see https://github.com/matt-richardson/gocd-websocket-notifier

### Install
```
sudo pip install -r requirements.txt
```

### Run
e.g
````
python gobot.py -w yourwebookurl -g my.gocd.domain -s my,stage,names
````

### Docker
Checkout the Dockerfile for running this service in a container ;)
