# TESS: Training Environment Server System

TESS serves as a simple local network to allow a trainer to work with services such as email, Jabber, a web server, in places where the internet is not functioning or electricity is weak.

## Components

TESS is built using a RaspberryPi with the Raspbian Debian distribution in addition to the following components:

* DNSMasq: DHCP and DNS
* Prosody: XMPP (Jabber)
* Postfix: SMTP
* Dovecot: IMAP
* Apache: HTTP
* iptables: firewall
