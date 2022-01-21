# Reviltwin
An opensource python script for pentesters that facilitates evil twin attacks against wifi vulnerabilities

Reviltwin uses **hostapd** to create new access point with possibility to configure by itself.

It uses **dnsmasq** to run the dhcp and dns services.

It uses **apache** with dnsmasq to create fake spoofed websites with option to capture possible user's credentials

All packets are sent and received via **Scapy**
