# Temperature-display-on-a-webserver
As part of the course of Hardware & Software , we tried to create a webserver on which we could be able to display the temperature with the help of an Arduino Uno, an ESP8266 and a mini set up on breadboard. Unfortunately, we have met some troubles with the data transmission from the Arduino to the ESP. In this github, we will show you what we did and the problems we have met. This project is still ongoing so, if anyone has an idea to improve the github you're welcome.

For this project you will find  :
## Ping pong code's file : 
This code uses a RX-TX connection to transfer the information from the Arduino UNO to the ESP8266. Unfortunately, the transmission between the two chips doesn't work. We do not know how to solve the problem. If someone has an idea you are welcome.
##  Functional Code:
This file contains the separated codes for the webserver and the temperature measurement. You will find videos showing the result on computer for each code.
##  Softserial Code :
Because we had problems with the RX-TX connection, we tried a Software Serial connection. But we encounter the same problem. It seems that : the data transmission is done through the TX of the Arduino UNO and not the pin we considered for the serial. You will find pictures of data frame seen on oscilloscope.
## About the project :
This project has been realized by the group 8 composed by Jostein Niyonzima and Luca Giambarresi.

The difficulties were essentially based on the way of making both tutorials work together. The communication between the ESP8266 and the Arduino Uno was (and is still) the main point of our problems. Both tutorials were good enough as « starting points » and we managed well to make them work separately (according to some small modifications). 
The added value would have been to combine the two tutorials. And if this objective would have been reached easily and in a short time, we would have liked to add a « graphical gauge » on the webpage showing the evolution of the temperature more visually (which would have made the project funny).
The time invested was quite substantial. We spent about 24 hours working on : the existing tutorials, the project itself and the « Ping-Pong test » developped just after the bad results concerning the project which normally worked with SoftwareSerial commands.


You can contact us at :
-[Github](Jostein.niyonzima@student.umons.ac.be)
-[Github](Luca.giambarresi@student.umons.ac.be)

## Useful sources :
-[Github](https://projetsdiy.fr/esp8266-serveur-web-interface-graphique-html/) : French tuto for the webserver
-[Github](https://www.carnetdumaker.net/articles/mesurer-une-temperature-avec-un-capteur-lm35-et-une-carte-arduino-genuino/ ) : French tuto for the temperature measurement and display 
-[Github](https://forum.arduino.cc/index.php?topic=354933.0) : French forum about the utility and the performance of the Software serial on ESP with Arduino IDE 

## Source : 
- [Github](https://github.com/j-niyosz/Temperature-display-on-a-webserver)
