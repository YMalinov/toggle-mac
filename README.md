Toggle-MAC
==========

BASH script, which toggles the MAC address of your network interface, between two values. Currently works only with eth0 or wlan0 interfaces. Before usage, remember to enter your default MAC addresses in the start of the script (you can get them from ifconfig).

Usage example:

toggle_mac -i eth0 # will toggle the MAC address of eth0 to the imaginary one

toggle_mac -i eth0 # should return the default MAC address of eth0
