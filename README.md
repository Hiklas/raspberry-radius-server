## Overview

Setting up a RADIUS server on two raspberry Pi devices and on another Single 
Board Computer (SBC) platform.

I have several WiFi access points and wish to have roaming working between 
these.  Apparently this means that I need to have a RADIUS server up and 
running and, ideally, redundantly deployed.

To add to the complexities I also have plans to using a Linux server (running
on the aforementioned SBC) carry out firewall and routing, using iptables and 
ebtables, across the different wireless networks.

This whole setup is a little over complicated but it's mainly a product of 
lack of faith in IoT devices - I simply don't want these to have full access 
to my network BUT there are apps running on phone/tablet/desktop that can be
used to access these devices.  Some traffic is needed, I just want to limit 
unwanted packets and reduce the risk of attack such a device become compromised.




## References

### WiFi Roaming

* [Roaming and authentication](http://www.revolutionwifi.net/revolutionwifi/2012/02/wi-fi-roaming-analysis-part-2-roaming.html)
* [How does roaming work](https://www.hometoys.com/demystifying-wi-fi-roaming/)


### RADIUS

* [RADIUS](https://networkradius.com/blog/security/wifi-security-with-radius/)

* [FreeRadius and LDAP](https://www.tldp.org/HOWTO/archived/LDAP-Implementation-HOWTO/radius.html)
* [FreeRadius](http://freeradius.org)






