# wghttp

[English](./README.md) \| [中文简体](./README_zh.md)

Turn WireGuard to HTTP & SOCKS5 proxies.

The HTTP & SOCKS5 proxies are served on same port. It runs in userspace,
without requirement of WireGuard kernel module or TUN device.

In remote exit mode, the proxy is served on local network, and the traffic
from proxy server goes to WireGuard network.

In local exit mode, the proxy is served on WireGuard network, and the traffic
from WireGuard goes to local network.

For detailed usage, see <https://github.com/zhsj/wghttp/tree/master/docs>.