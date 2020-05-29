# Diploma_thesis_px4

This repository contains all source codes, that has been used during my diploma thesis.

## Clone and download all submodules



Clone whole repository:

```
git clone https://github.com/rligocki/Diploma_thesis_px4/tree/master
```


Download all submodules:

```
git submodule update --init --recursive
```

Your are ready to view all results. ;)

## Submodules description

###### Certificate generator

Example code that shows how certificates for unmanned vehicle should look like and how to sign them using authority certificate.

###### Firmware

PX4 autopilot firmware for pixhawk or other autopilot boards. During development it was necessary to modifie firmware interactions with generated mavlink library and add CERTIFICATE message broadcasting.

###### NIST-statistical-test

This repository contains source code and data, that have been used to prove quality of random generators on pixhawk autopilot board and random generators in Qt framework. 

###### mavlink 

In this repository, that contains all MAVLink message definitions it, a CERTIFICATE message has been added into common.xml.

###### px4_example

Example code to test and show posibilities of MonoCypher and LibHydrogen cryptographic libraries. This code also tests performance on different platforms.

###### pymavlink

Main part of practical part of my thesis was done here. PyMAVLink contains mavlink_helper.h, that manage creation, sending, receiving and parsing of MAVLink messages. In this file most 

###### qgroundcontrol

Source code of qgroundcontrol mission planner software. Same as in Firmaware repository, in this source code it was necessary to change how qgroundcontrol interacts with mavlink_helper.h library. 

