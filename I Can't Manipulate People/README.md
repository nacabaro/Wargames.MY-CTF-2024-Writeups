# Wargames.MY CTF 2024 I Can't Manipulate People

## Description

Partial traffic packet captured from hacked machine, can you analyze the provided pcap file to extract the message from the packet perhaps by reading the packet data?

## Files attached

- `traffic.pcap`

## Solve procedure

Opening the file will show a lot of failed connections to a machine

![](image-6.png)

Checking the requests to the machine we cannot find the flag in plain text.

To obtain the flag we are going to copy the data transfered in the ICMP requests.

![](image-7.png)

## Flag

`WGMY{1e3b71d57e466ab71b43c2641a4b34f4}`