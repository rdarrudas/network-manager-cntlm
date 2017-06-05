network-manager-cntlm
=====================

[Cntlm][cntlm] integration for [NetworkManager][nm] framework

[NetworkManager][nm] is a system network service _(a.k.a. daemon)_ that manages your network devices and connections, attempting to keep active network connectivity when available. It manages ethernet, WiFi, mobile broadband (WWAN), and PPPoE devices, and provides VPN integration with a variety of different VPN services.

[Cntlm][cntlm] is a fast and efficient NTLM proxy, with support for TCP/IP tunneling, authenticated connection caching, ACLs, proper daemon logging and behaviour and much more. It has up to ten times faster responses than similar NTLM proxies, while using by orders or magnitude less RAM and CPU.

This package provides a [NetworkManager][nm] dispatcher for [Cntlm][cntlm], providing up-to-date proxy settings even when changing network connections.

How to build?
-------------

1. `git clone` this stuff
2. `mvn clean package`
3. `dpkg -i` the debfile that will rise under `target`

[cntlm]: http://cntlm.sourceforge.net/ "Cntlm Authentication Proxy"
[nm]: https://wiki.gnome.org/Projects/NetworkManager "NetworkManager — network management daemon"
