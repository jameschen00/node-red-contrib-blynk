# node-red-contrib-blynk
Blynk app integration with Node Red

# This contrib will no longer be updated. Please use the [websockets version](https://github.com/tzapu/node-red-contrib-blynk-websockets).

## Websockets version
__Due to some reliability issues reported by some users, together with some new features added by the Blynk team, I started another version of this based on websockets.__
https://github.com/tzapu/node-red-contrib-blynk-websockets

## Normal Blynk Protocol version

[![NPM](https://nodei.co/npm/node-red-contrib-blynk.png?mini=true)](https://npmjs.org/package/node-red-contrib-blynk)
[![npm version](https://badge.fury.io/js/node-red-contrib-blynk.svg)](https://badge.fury.io/js/node-red-contrib-blynk)

If you installed Node Red globally use this to install
```npm install --global node-red-contrib-blynk```

Supports both SSL, non SSL connections to blynk-cloud.com and local server.

### Supported events and widgets
- read event
- write event
- write command
- LCD widget (advanced mode)
- push notifications

### Blynk App Settings
Use Raspberry PI as hardware to access 64 virtual pins or Generic Board for 32.

### How to use

#### LCD Widget ![LCD Print Widget Node](http://i.imgur.com/IjSrqAx.png)

- use advanced mode on LCD Widget in iOS/android Blynk App
- set message.payload to the text you want displayed
- set message.topic to the line you want it shown on (0 or 1, defaults to 0)
- set message.payload to 'clear-lcd' if you want to clear it

### Debug
Use the verbose `-v` flag when starting Node-Red to get more information

### Available Nodes
![Available Nodes](http://imgur.com/tY2qwCU.png)
