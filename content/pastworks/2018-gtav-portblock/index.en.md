---
layout: "pastworks"
date: "2018-07-27"
title: "GTA-V portblock"
tags:
  - "hobby"
showcase:
  - src: "2018_gtav-portblock_1.webp"
    alt: "Windows Firewall batch script for GTA-V port blocking and whitelisting IPv4 addresses."
---
This project involved creating a batch file to manage Windows Firewall for GTA-V, allowing port blocking and whitelisting of IPv4 addresses to enable private online sessions without modifying the game itself.

- Created a bat file to simplify management of Windows Firewall for blocking ports and whitelisting IPv4 addresses for PC game Grand Theft Auto V
- Features such as CEO missions and Biker businesses can only be played in an online session with other players. This can be disruptive especially when there are cheaters (modders) in the game and you want to play your game in peace
- There is no modification to the underlying game and in fact just stops certain outbound traffic that the game uses to connect to other online sessions and allows specific IPv4 addresses (such as your friend's) to connect to your "private" online session
- [GitHub repo](https://github.com/reverie89/gtav-portblock)
