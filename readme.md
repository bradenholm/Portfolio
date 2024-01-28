# Welcome, below is a list of some of the projects I have done.

Table of Contents:
- [SKYNET](https://github.com/bradenholm/Portfolio#server-1-skynet)
- [Home Assistant](https://github.com/bradenholm/Portfolio#server-2-home-assistant)
- [Mac Mini](https://github.com/bradenholm/Portfolio#mac-mini)
- [Router](https://github.com/bradenholm/Portfolio#router)
- [Mobile Phone](https://github.com/bradenholm/Portfolio#mobile-phone-grapheneos)


### Server 1: SKYNET
This server is setup as my main server. It has [CasaOS](https://github.com/IceWhaleTech/CasaOS) installed to make installing docker containers easier. 
   - More info about CasaOS: It uses it's own official repositories and allows third party ones, but also allows easy importing of official or custom docker containers from whatever source you want. The safest practice here is to choose only official containers.

Directly installed with CasaOS is [Uptime Kuma](https://github.com/louislam/uptime-kuma) which is a very simple docker container that is used to monitor devices and services. It can be configured to send an http, ping or keyword request to any site (including port) and report back via a telegram bot if the status changes. 

I have Uptime Kuma setup to monitor [Home Assistant](https://www.home-assistant.io/), [Pi-Hole](https://github.com/pi-hole) a Mac Mini, a Raspberry Pi and my personal computer with notifications for critical services. 

Pi-hole is another service running on this computer. This is a simple way to get network-wide Ad and tracker blocking as well as blocking any DNS request you like.

Syncthing is used to transfer files between devices. It uses public relays to allow the transfer to happen without opening ports and as a peer to peer transfer. 

[Nextcloud](https://github.com/nextcloud) is a replacement for almost all of Google products but run on my own computer and inaccessible to the public internet. I use it to sync all my contacts and calendars, as well as file storage and the ability to do live GPS tracking completely privately.

[Actual Budget](https://github.com/actualbudget/actual) is used to keep track of my budget and one can pay for this service, or host it on any server.

[Jellyfin](https://github.com/jellyfin/jellyfin) is used as a more useful Netflix. I have Jellyfin setup to allow me to view my old photos, music and podcasts, as well as play any media files that I own.

[WikiDocs](https://github.com/Zavy86/WikiDocs) is used as my own personal wiki. It has some of my favorite recipes saved to it, such as Creamy Tuscan Chicken.

Security software installed includes a MFA solution called [2FAuth](https://github.com/Bubka/2FAuth). This is a secure alternate way of storing TOTP tokens and viewing the rolling codes to login. Obviously this is very sensitive data, so it is treated as a alternate method of accessing TOTP codes, and not a backup while using a very, very secure password.

[Wireguard](https://www.wireguard.com/) is my preferred method for accessing the important information on my servers. Wireguard has been proven to be very robust and a reliable VPN solution. I use [pivpn](https://github.com/pivpn/pivpn) for setup of wireguard.


### Server 2: Home Assistant

Smart home! This is the way to go if you care about privacy and want a smart home. Powerful automatons can do way more than your cheap Alexa, all while running tasks locally or without internet completely.

I have 1 button, 1 temperature sensor and 8 smart plugs all using the Zigbee protocol and have near 100% uptime.


### Mac Mini:

This runs a program called [AirMessage](https://airmessage.org/) that privately and securely brings iMessage to android.
Future plans include purchasing more of these, as they are extremely power efficient, and installing linux to run normal server tasks.


### Router:

My Asus router runs the open source firmware [Asuswrt-Merlin](https://www.asuswrt-merlin.net/) which adds more features, security and reliahttps://airmessage.org/bility to Asus routers. A future project is to purchase a [Protectli Vault](https://protectli.com/) and use [pfsense](https://www.pfsense.org/) as an even better router and firewall.


### Mobile Phone: [GrapheneOS](https://grapheneos.org/)

This one is a lot.
To keep it brief, GrapheneOS is a fork of the Android Open Source Operating system. It has been modified to be more hardened than this stock operating system. This improves security and privacy. 
Things such as:
   - Installing Google services as a normal user and not Admin [source](https://grapheneos.org/features#sandboxed-google-play) to improve functionality and maintain privacy
   - Using "per-connection MAC randomization" [source](https://grapheneos.org/features#wifi-privacy) for better privacy when using WiFi
   - [Storage Scopes](https://grapheneos.org/features#storage-scopes) which gives an app permission to only the specified files, while bypassing any apps attempts to stop this
   - [Auto Reboot](https://grapheneos.org/features#auto-reboot) to help mitigate exploits like Pegasus
   - A [camera](https://grapheneos.org/features#grapheneos-camera) that doesn't capture un-needed metadata
   - And many more. see [here](https://grapheneos.org/features) for the full feature list
   
