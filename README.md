# IOT-Tessel-board-hacking
It's a simple IOT implementation using Tessel board (https://tessel.io/)

There are two part of my code, and I put them separately into "tessel" and "server":

1. tessel: It's the client side of this whole IOT, and thus it can be seen as a wearable device, sending data/request to the server. There are totally 4 kinds of sensor modules (accelerometer, camera, climate, rfid); each one should work with the audio module, which respond to response from server, playing sounds related to sensor data.

2. server: handling request from Tessel board, saving data to localhost, displaying data on webpage using some source like d3.js


Note that:

1. You should set the host name and port for both "tessel" and "server", so that they can communicate

2. You should handle the Tessel setting and some configuration before running the program, that's no part of this repo.
