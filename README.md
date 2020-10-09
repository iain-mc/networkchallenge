# GUTS 2020 Network Challenge

## Difficulty: 
Easy

## Overview:
This challenge is an exercise in basic network protocol analysis. The aim is to analyse the .PCAP file and find the data being transfered over the network. To complete the challenge simply find the names of 11 countries and tell us which protocol they were hidden in. Some are much easier than others. Good luck! 

Fill out a table like below to be marked:

Country Name | Network Protocol
------------ | -------------
scotland| Address Resolution Protocol
.|.
..|..
...|...
  
## Getting Started
Clone the repository

`git clone https://github.com/iain-mc/networkchallenge.git `

Open 'capture.pcap' in a network analyser of your choice 

For example, for example you may want to use WireShark:
	
`sudo apt-get update`
	
`sudo apt-get install wireshark`

Once you have Wireshark installed, open it then click File -> Open and select capture.pcap.

# Hints
Some are very easy to find, for example just looking for plaintext in the payload of common transport protocols.

Some are a bit more tricky as the data can be split across many TCP packets, encoded in formats such as JPEG, etc..  
