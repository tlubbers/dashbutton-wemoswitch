# Dash Button Wemo Switch 

This repository houses a script that highlights methods to leverage packet sniffing and Amazon's Dash Buttons to control Wemo Lights connected to an Ouimeaux server.

The script requires edits to work with different light setups, but the samples in the script should give any Python developer a decent starting point. 

##  Requirements 
### Ouimeaux 
[Ouimeaux](https://github.com/iancmcc/ouimeaux) is an open source controller for Belkin Wemo devices. 

### Scapy 
[Scapy](https://github.com/secdev/scapy) is a packet manipulation program and library. The script uses scapy to identify the Dash buttons when they attempt to connect to wifi. 

### Dash Buttons
Follow [Ted Bunson's original article](https://blog.cloudstitch.com/how-i-hacked-amazon-s-5-wifi-button-to-track-baby-data-794214b0bdd8) on Dash Buttons to get setup for the hack. 
