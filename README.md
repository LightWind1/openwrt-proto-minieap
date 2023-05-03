# minieap for OpenWrt

Works with [luci-proto-minieap](https://github.com/LightWind1/luci-proto-minieap)
Test success on OpenWrt 22.03.0 r19685-512e76967f / LuCI openwrt-22.03 branch git-22.245.77528-487e58a.
Thanks to @ysc3839 and @AutoCONFIG.

## Build

First download [OpenWrt SDK](https://downloads.openwrt.org/) for your device.

```sh
cd /path/to/your/sdk
git clone https://github.com/LightWind1/openwrt-proto-minieap.git package/minieap
make menuconfig # choose `minieap` in section `Network`
make package/minieap/compile V=s
```
