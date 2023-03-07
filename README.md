# Configuring OpenVPN To Support Remote Access Clients On A Ubiquiti Dream Machine Pro

The Unifi Dream Machine Pro (UDM) has OpenVPN installed but only enables its use for point-to-point VPN connections between the UDM and another network. The Unifi console software does not provide a way to configue OpenVPN as a VPN server that clients on the public internet can use to access the local LAN. This can be done manually, however. The challenge is doing so in a manner that will persist through UDM firmware upgrades and reboots.

This project contains the files that I used to build a Debian package that I host in my PPA repository that applies the necessary configuration changes.   Please go to [this page](https://daveking.com/udm-hacks/openvpn-udm.html) for more details on using that package to configure OpenVPN in this manner.
