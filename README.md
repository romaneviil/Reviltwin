# Reviltwin
An opensource Python3 script for pentesters that facilitates evil twin attacks against wifi vulnerabilities

Reviltwin uses **hostapd** to create new access point with possibility to configure by itself.

It uses **dnsmasq** to run the dhcp and dns services.

It uses **apache** with dnsmasq to create fake spoofed websites with option to capture possible user's credentials

All packets are sent and received via **Scapy**

## Features
**All forms of evil twin AP**

The Reviltwin script, with the help of hostapd can pretend it is native network with any type of wifi. By using the hostapd-wpe patch it is really easy to get the wpa credentials.

## Installation and usage
Clone the project and run following command inside the directory of cloned repository
`python3 reviltwin.py`

Once the script is running, you should enter an option with **search for dependencies and requirements**. Process of Reviltwin will automatically scan for missing requirements and then will try to install them.
