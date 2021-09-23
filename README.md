# Openwrt-config
My config for compiling https://github.com/coolsnowwolf/lede

### SSR

In order to compile ssr, you need to add or uncomment 
```
src-git helloworld https://github.com/fw876/helloworld
```
in ./feeds.conf.default

### Repositories

Here is the official opkg mirror list in `/etc/opkg/distfeeds.conf`. Note that this list is for x86_64.

```
src/gz openwrt_core http://downloads.lede-project.org/snapshots/targets/x86/64/packages
src/gz openwrt_base http://downloads.lede-project.org/snapshots/packages/x86_64/base
src/gz openwrt_telephony http://downloads.lede-project.org/snapshots/packages/x86_64/telephony
src/gz openwrt_packages http://downloads.lede-project.org/snapshots/packages/x86_64/packages
src/gz openwrt_routing http://downloads.lede-project.org/snapshots/packages/x86_64/routing
src/gz openwrt_luci http://downloads.lede-project.org/snapshots/packages/x86_64/luci
```

Below is a mirror list for Chinese users:

```
src/gz openwrt_core https://mirrors.cloud.tencent.com/lede/snapshots/targets/x86/64/packages
src/gz openwrt_base https://mirrors.cloud.tencent.com/lede/snapshots/packages/x86_64/base
src/gz openwrt_luci https://mirrors.cloud.tencent.com/lede/releases/18.06.9/packages/x86_64/luci
src/gz openwrt_packages https://mirrors.cloud.tencent.com/lede/snapshots/packages/x86_64/packages
src/gz openwrt_routing https://mirrors.cloud.tencent.com/lede/snapshots/packages/x86_64/routing
src/gz openwrt_telephony https://mirrors.cloud.tencent.com/lede/snapshots/packages/x86_64/telephony
```
