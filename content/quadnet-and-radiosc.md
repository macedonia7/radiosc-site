---
date: '2026-05-14T08:29:47-04:00'
draft: false
title: "Quadnet Digital Services and RadioSC"
tags: ["M17", "DMR", "YSF", "D-STAR"]
categories: ["Multimode", "Connect"]
---

# Quadnet

Quadnet sevices are an indispensable part of RadioSC. Our DMR Talk Group (TG) 517 and two of the methods that connect via Yaseu System Fusion reside on [Quadnet](https://openquad.net) servers.  Quadnet facilitates our multimode system by maintaining a full-time link to our URF517 Reflector, a link to the TGIF 517 Talkgroup, and coordination with the other [DMR Unificaton Project](https://dmrup.org) Networks so that our RadioSC network is available on servers worldwide.

The connections shown below expand the detail than the simple list of connections in the [Connecting to RadioSC post](posts/how-to-connect-to-radiosc.md) but there are not intended to be exhaustive.

- ***If assistance is needed for connecting to RadioSC please contact us on our [Discord Server](https://discord.gg/aujUBDebb) where we can provide individualized assistance.***

## Connecting to RadioSC via DMR

There are at least four ways to connect to RadioSC via a DMR radio with a hotspot.

1. TG 517 via the [Quadnet Rysen server](https://quadnet.ddns.net/dashboard/index.php). 
2. TG 517 via the [Quadnet IPSC2 server](https://dmr.openquad.net/).
3. TG 517 via TGIF.
4. Via XLX Master connect to XLX517A. 

## Connecting to RadioSC via Yaesu System Fusion (YSF) with a YSF radio and a hotspot

1. YSF31001 - US - C4FM - QUADNT - YCS310, DG-ID 81 on the [YCS310 Quadnet Server](https://ycs.openquad.net/).
2. FCS31081 also on the [YCS310 Quadnet Server](https://ycs.openquad.net/).
3. YSF51700 Reflector - this method connects directly to the XLX517A.

## Connecting to RadioSC via a D-STAR radio and a hotspot

- D-STAR DCS517A or XRF517A - Be sure to set your radio to "Use Reflector" with a Dup of + or - and an offset of "0."

## D-STAR RF Repeaters

We currently have two D-STAR repeaters in South Carolina capable of linking to our RadioSC Reflector and at least one more on the way.

1. KR5CHS, 145.120 (-), located in Awendaw, SC is fulltime linked to DCS517.  
2. [W4GL](https://www.sumterhamradio.net/), 444.150+ PL123.0 D-Star/FM, located in Sumter, SC is linked to RadioSC for Nets.  Capable of linking to reflectors by operators.
3. W4IR - Hilton Head Island, SC - Installation in progress.
4. Other groups are welcome to join.  Please contact us via [Discord](https://discord.gg/aujUBDebb) 

## Connecting to RadioSC via a M17 radio and a hotspot, et al

1. URF517A via a M17 radio and hotspot (multiple options).
2. URF517A with DroidStar via an Android or iPhone.
3. [mvoice](https://github.com/n7tae/mvoice) via a Linux computer running Debian, Ubuntu, or Raspbian (PiStar devices). Requires a USB headphone with mic.