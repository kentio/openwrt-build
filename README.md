# openwrt

![](https://github.com/kentio/openwrt-build/workflows/K2P/badge.svg)

- make defconfig
- diffconfig.sh

# run
```shell script
git clone https://github.com/coolsnowwolf/lede.git
./scripts/feeds update -a && ./scripts/feeds install -a
make menuconfig
```

# ref
- [openwrt-centos7-编译环境搭建](http://imdouba.com/archives/openwrt-centos7-%E7%BC%96%E8%AF%91%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA.html)
- [让Actions帮你编译固件](https://www.youtube.com/watch?v=9YO7nxNry-4)
- [OpenWrt/LEDE 编译小记（斐讯 K2P）](https://mary.kevinmx.tk/index.php/archives/k2p.html)
- [openwrt-phicomm-k2p-build](https://github.com/KevinMX/openwrt-phicomm-k2p-build)
- [AutoBuild-OpenWrt](https://github.com/esirplayground/AutoBuild-OpenWrt)

```text
luci-app-arpbind
luci-app-autoreboot
luci-app-ddns (including extra scripts)
luci-app-firewall
luci-app-flowoffload
luci-app-ramfree
luci-app-sqm
luci-app-ssr-plus (v2ray+trojan+ShadowsocksR&server)
---luci-app-v2ray-server
luci-app-upnp
---luci-app-vlmcsd (KMS Server)
luci-app-wifischedule
luci-app-wol (Wake on Lan)
luci-theme-argon
luci-app-zerotier
ipv6helper
wireless driver built-in
```
