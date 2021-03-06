![](https://www.wireguard.com/img/wireguard.svg)

WireGuard® is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN. WireGuard is designed as a general purpose VPN for running on embedded interfaces and super computers alike, fit for many different circumstances. Initially released for the Linux kernel, it is now cross-platform (Windows, macOS, BSD, iOS, Android) and widely deployable. It is currently under heavy development, but already it might be regarded as the most secure, easiest to use, and simplest VPN solution in the industry.

### WireGuard Install

```
# Custom Port Install WireGuard Script (port 9999 used as an example on the next 2 lines. Line 1 uses eth0. Line 2 uses wlan0.)
bash <(curl -L -s https://raw.githubusercontent.com/hyukishi/wireguard_pi/english/wireguard-install-eth0.sh) 9999
bash <(curl -L -s https://raw.githubusercontent.com/hyukishi/wireguard_pi/english/wireguard-install-wlan0.sh) 9999
```

[WireGuard](https://www.wireguard.com) installer for Raspbian Jessie.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used WireGuard before. It has been designed to be as unobtrusive and universal as possible.

------

![](https://github.com/teddysun/shadowsocks_install/raw/master/shadowsocks.png)
### shadowsocks-libev

[Shadowsocks-libev](https://shadowsocks.org) is a lightweight secured SOCKS5
proxy for embedded devices and low-end boxes.

It is a port of [Shadowsocks](https://github.com/shadowsocks/shadowsocks)
created by [@clowwindy](https://github.com/clowwindy), and maintained by
[@madeye](https://github.com/madeye) and [@linusyang](https://github.com/linusyang).

------
### Project V  (V2Ray)
Project V is a set of network tools that help you to build your own computer network. It secures your network connections and thus protects your privacy. See [our website](https://www.v2ray.com/) for more information.

```
# Easy Install Shadowsocks & V2Ray : Generate and display QR code
bash <(curl -L -s https://git.io/v2ray_ss.sh)
```
