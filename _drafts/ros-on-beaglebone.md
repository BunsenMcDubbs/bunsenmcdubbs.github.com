---
layout: post
title: "ROS on UbuntuARM 13.04 on Beaglebone"
category: beaglecar
tags: [beaglebone, ROS, ubuntu]
---

After flashing Ubuntu 13.04 onto the Beaglebone, I installed ROS Hydro. The
dependency issues I had the first time around seem to have been resolved
(collada wasn't available on UbuntuARM). Installing ROS was painless, but
involved.

### My setup

My Beaglebone Black is tethered to a desktop Ubuntu machine through a USB
connection. I access the BBB exclusively through SSH'ing. (Note: the Ubuntu
image I flashed onto the BBB did not have avahi installed so SSH'ing with
`ssh ubuntu@beaglebone.local` does not work. I have to use the IP address: 
`192.168.7.2` aka `ssh ubuntu@192.168.7.2` or `ssh 192.168.7.2 -l ubuntu`)
To access the internet I hacked together a shell script adapted from
instructions I [found online.]
(http://robotic-controls.com/learn/beaglebone/beaglebone-internet-over-usb-only)

TODO upload scripts to gist and link here.

