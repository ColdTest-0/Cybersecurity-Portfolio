---
layout: default
---

<a href="https://coldtest-0.github.io/Cybersecurity-Portfolio/">Main Page</a>
 | <a href="https://coldtest-0.github.io/Cybersecurity-Portfolio/ProjectPage">Projects Page</a>
 | <a href="https://coldtest-0.github.io/Cybersecurity-Portfolio/ContactPage">Contact Page</a>

# SIEM Home Lab Project

This project documents my experience performing the [SIEM Home Lab](https://medium.com/@aw23/siem-homelab-part-1-c6392b9957d7) overview on Medium.com. This learning collection teaches how to make a small SIEM network in Oracle VirtualBox, a powerful network virtualization tool.

## Part 1: Setup

 This part consist of multiple steps which set up each part of the network.
 
- Task 1: PfSense Setup
  - After downloading and installing Cisco Packet Tracer, I am taught how to set up a basic home network.
  - I place a home router, PC, laptop, and microphone into the simulated environment.
  - I connect the router to the PC with a wired connection and set the laptop to be wireless. It connects automatically.
  - I set the SSID on the microphone to match the router, allowing it to connect wirelessly.
<img src="../ImageFolder/BasicHome2.png" alt="Basic Home Network" style="width:500px;height:auto;">

- Lab: Logical and Physical Mode Exploration
  - This lab explains the difference between logical and physical mode in the app.
  - Logical mode displays the flow of data within the network, using devices as anchor points.
  - Physical mode displays the arrangement of devices and cables within a space.
  - The lab comes with an prebuilt intercity network, and focuses on physical mode.
  - In the office, I connect a PC to the ethernet and edge router. I then install a second router and connect it to a laptop.
  - Using the laptop, I access the second router and use console commands to change its settings.
<img src="../ImageFolder/Intercity5.png" alt="Router Settings" style="width:500px;height:auto;">
  
- Lab: Build a Home Network
  - In this lab, I establish a home network and connect it to the internet.
  - I place a laptop, PC, and modem into an environment which already contains a router and internet connection.
  - Using cables, I connectthe PC to the wireless router, the router to the modem, and the modem to the internet.
  - Utilizing physical mode, I switch the laptop to be wireless, allowing to to connect to the router.
  - To confirm a connection, I use the virtual web browser on the laptop.
<img src="../ImageFolder/Home2.png" alt="Online Home Network" style="width:500px;height:auto;">




