# LandPing
*Lan* *And*roid *Ping*
This background service allows someone to access a locally (as in on-device) server (finder) and poll all other devices on the network. Any other device running this service will receive the request and respond, verifying that device is running the service (findee). Then the finder can tell the findee to make noise at maximum volume, allowing someone to locate a lost device. This happens on the same network, so both devices must be on the same LAN. VPNs could interfere. 

# Features (/to implement) plan
## 0.1.0
Notification service
## 0.2.0
Web service (no web page)
## 0.3.0
Web Pages
## 0.4.0
LAN communication