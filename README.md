# KinuxShield

###### UNOFFICIAL - KDE GUI for HotspotShield Linux by Kiraitachi
<p align="center">
  <img src="[https://github.com/kiraitachi/PyShield/blob/main/Pyshield.jpeg]">
</p>

---

## Description and Purpose

Long time ago I bought a lifetime license for Hotspotshield. I wont go into details of what VPN services are more realiable :yawning_face:(NordVPN, Windscribe, IPVanish, etc), but at the time, I wasn't fond of subscriptions based licenses and a lifetime license seemed like a really good deal :money_mouth_face:. Back then no Linux support available (mid 2016), recently Hotspotshield was bought by Aura which added Linux support to their client :heart_eyes: :heart_eyes:.

Sadly, almost all VPN clients I tried for Linux have no GUI support :confused:, which is fine for most of the cases, but sometimes its just a pain and want a seamless experience. Here is where KinuxShield is born :boom:, from the humble hands of a Cybersecurity Analyst that has limited knowledge on developing apps, but is a KDE lover ever since 2008 :nerd_face:.

---

## Requirements are the following:

* KDIALOG installed, on KDE usually comes pre-installed: `sudo apt install kdialog`
* Hotspotshield Linux Client: https://www.hotspotshield.com/vpn/vpn-for-linux/?af-campaign=linux-banner-click
            
---
           
## What can we do with HotspotShield client and what is ported to KinuxShield

- [x] Start the VPN, does not connect it `hotspotshield start`
- [x] Stops the VPN in the background, disconnects if connected `hotspotshield stop`
- [ ] Connect to a Virtual Location or city `hotspotshield connect [country code]`
- [x] Connect to the most recent location `hotspotshield connect`
- [x] View account information and status `hotspotshield account status`
- [x] Displays the list of all available Virtual locations `hotspotshield locations`
- [x] Disconnect or change to another Virtual Location `hotspotshield disconnect`
- [x] Check if the VPN is running `hotspotshield status`
- [x] Check your public IP `curl ipinfo.io`

Source of commands: https://support.hotspotshield.com/hc/en-us/articles/360041968071-What-are-all-of-the-Hotspot-Shield-commands-on-Linux-
