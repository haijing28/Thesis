This project is designed to bring an alternative interaction experience for network communications, and engage participants to have a speculative concern on the interaction modes of social meida.



The internet Data is from Twitterstreaming live data, I used a npm module for REST and Streaming API on node https://github.com/ttezel/twit

Physical Interface is designed with an arduinoFio（http://arduino.cc/en/Main/ArduinoBoardFio), RN-XV WiFly Module (https://www.sparkfun.com/products/10822) and a triple axis accelerometer（https://www.sparkfun.com/products/9269） 

I get the data from z-pin of from accelerometer. since, a real-time twitter datavis requires a communication of Transmission Control Protocol. In this case, I required the websocketAPI that provides full-duplex communication channels over TCP connection, and allows my physical interface sensorData get handshake with the server.


for more information please check:
http://haijing.info/Portfolio/?page=copterwish

