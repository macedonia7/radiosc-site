---
date: '2026-05-07T11:20:55-04:00'
draft: false
title: 'About'
tags: ["digital"]
categories: ["Operating", "Multimode", "URF517"]
---

## RadioSC Composition

### Key Features

-   **Hardware Transcoding**: Our system uses dedicated hardware (DVMEGA DVStick 30) to ensure high-quality audio when moving between D-STAR (AMBE) and other modes.
    
-   **Universal Reflector (URF)**: Based on the modern `urfd` architecture, allowing A-Z module flexibility, up to 26 channels per reflector.
    
-   **Analog-Digital Bridge**: Direct integration with Allstar and Echolink ensures that legacy analog repeaters and operators with their own Allstar devices can participate in the digital conversation.
    
-   **M17 Support**: We are proud supporters of the M17 Project, offering a fully open-source digital path for hams who prefer non-proprietary protocols.

### Reflector

The Hub of the RadioSC system is our Universal Reflector, [URF517](http://urf517.radiosc.net/).  URF517 runs the [2urfd Reflector software](https://github.com/n7tae/2urfd).

URF517 has two trancoders on Module/Channel A, one for transmit and one for receive, allowing D-STAR, YSF, DMR, and M17 to have QSOs (P25 and NXDN could also be activated if needed).  DMR and YSF can commuicate on other channels since they use the same CODEC (so a hardware transcoder is not required).

### IcomGateway

Our first D-STAR repeater located at Awendaw, SC also connects to the reflector via the [IcomGateway software](https://github.com/n7tae/IcomGateway). 

### Allstar and Echolink

Allstar provided connectivity for the 440 FM Repeater in Bluffton, SC as well as connectivity to URF517 and supports Echolink.

### M17 Reflector

Our [M17-517](https://m17-517.radiosc.net/) Reflector, installed on a VPS, runs the [mrefd reflector software](https://github.com/n7tae/mrefd). 


## Some of our RadioSC Objectives

1. Utilize Repeaters on the system - increase usage and have fun!

2. Familiarization of all the Digital modes, Allstar, and Echolink.

3. Provide daily use and another backup resource for the South Carolina Low Country region.

4. Provide mode-agnostic QSOs

5. Participate Multi Mode Net(s).

6. Provide mentoring, a knowledge base, and support to all Amateur Radio Operators wishing to explore the digital modes. 

