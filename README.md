# Enviro_Sensor

A simple web server that displays real-time raw data from the serial of the COZIR C02/Temp/Humidity sensor, LDR and PIR motion sensors. It is intended to be run on a Freetronic Etherten 3.0, powered by POE, which collects the data, connects to the netowrk via the ethernet cable and hosts the webserver.

## Getting Started

Install on Freetronic Etherten 3.0 or Arduino Ehternet, connect to ethernet, modify the IP Address in the code to one valid for your network and upload the code.

Connect COZIR sensor serial ports Rx and Tx to D9 an D8 respectively.
Connect the PIR sensor output to D2 (interrupt pin).
Connect the LDR sensor output to A0.

Once running, go to the IP Address to view the webpage and raw data. Use node-red to develop an easy way to collect, organise and display the data.

Your webpage should appear similar to this:

----------------

#Arduino Sensor Hub WebServer


##COZIR Raw Data:

H 00379 T 01217 Z 00983
##PIR Sensor Status:

LOW
##LDR Raw Analog Value:

504 

----------------


## Built With

* Arduino IDE

## Authors

* **James R. Barrett** - [jamesRbarrett12](https://github.com/jamesRbarrett12)
* **Jerome Clinton**

## Acknowledgments

* Hat tip to Aidan - boss and fellow nerd
* my mum
* my dog
* food

