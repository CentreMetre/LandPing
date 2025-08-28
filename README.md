# LandPing
*Lan* *And*roid *Ping*
This background service allows someone to access a locally (as in on-device) server (finder) and poll all other devices on the network. Any other device running this service will receive the request and respond, verifying that device is running the service (findee). Then the finder can tell the findee to make noise at maximum volume, allowing someone to locate a lost device. This happens on the same network, so both devices must be on the same LAN. VPNs could interfere. 
