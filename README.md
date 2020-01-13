# simple-mqtt-ws
Simple mqtt over webscockets client

This is a simple implementation of a mqtt over websocket client written in JavaScript.
The motivation was to understand how mqtt over websockets work. All I could find were library based implementations.
They are most likely better suited for most cases. But maybe somebody finds it usefull to have a really simple client as a basis for own developments.
200 lines of html and javascript code all in one file (index.html) to have an mqtt client.
It can not publish data and it does not support larger strings (only length up to 127), but it can connect and subscribe.
