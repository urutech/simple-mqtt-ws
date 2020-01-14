# simple-mqtt-ws
Simple mqtt over webscockets client

This is a simple implementation of a mqtt over websocket client written in JavaScript.
The motivation was to understand how mqtt over websockets work. All I could find were library based implementations.
They are most likely better suited for most cases. But maybe somebody finds it usefull to have a really simple client as a basis for own developments.
200 lines of html and javascript code all in one file (index.html) to have an mqtt client.
It can not publish data and it does not support larger strings (only length up to 127), but it can connect and subscribe.

##### How to run the code?

The general intention is to host the code on a web server that also runs a mosquitto broker. That's why the websocket connection is initiated to the same hostname. The mosquitto broker needs to be setup for websockets on port 9001. Besides of that, there is no other dependency.
