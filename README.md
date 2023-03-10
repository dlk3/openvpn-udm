# Configuring OpenVPN To Support Remote Access Clients On A Ubiquiti Dream Machine Pro

The Unifi Dream Machine Pro (UDM) has OpenVPN installed but only enables its use for point-to-point VPN connections between the UDM and another network. The Unifi console software does not provide a way to configue OpenVPN as a VPN server that clients on the public internet can use to access the local LAN. Instead, the UDM offers "Transport," a WireGuard-based solution for remote client access.  I don't use this, mostly based on a series of personal preferences.  I still prefer to use OpenVPN, which can be done, as it was before, by manually configuring a server on the UDM.

This project contains the files that I use to build a Debian package that I host in my PPA repository that applies the necessary configuration changes.   Please go to [this page](https://daveking.com/udm-hacks/openvpn-udm.html) for more details on using that package to configure OpenVPN in this manner.
