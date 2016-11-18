# HomeAutomation

This project includes a significant amount of hardware as well as code. The project can essentially be broken down in 3 sections:
 - RaspberryPi HTTP server - SpringBoot providing a REST entrypoint for communications over the Internet, and relaying incomming messages out to the serial comms GPIO header.
 - GPIO connected RF Tx/Rx modules - a RF 433 Mhz transmitter and receiver module for sending/receiving messages from/to the Java application running on the RaspberryPi.
 - A number of agents, running on an Atmel micro-proccessor and with an RF Tx/Rx pair to allow for communications with the RaspberryPi server as well as forwarding packets to other agents.
 
 
 ## RaspberryPi server
 More to come here.
 
 ## GPIO RF interface
 More to come here.
 
 ## RF agents
 More to come here.
