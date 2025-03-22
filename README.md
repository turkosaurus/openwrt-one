# openwrt-one
notes, commands, and scripts for OpenWRT One router

## docs
- [Quick Start](https://openwrt.org/docs/guide-quick-start/start)
- [Howto](https://one.openwrt.org/hardware/OpenWrtOne-HowTo.pdf)


> [!NOTE]
> Notes based on use of Ubuntu 24

## serial
Connect over USB serial console:
```sh
sudo minicom -D /dev/ttyACM0 -b 115200
```

Press `enter` to bring up the prompt:
```
OpenWrt One> version
U-Boot 2024.10-OpenWrt-r28161-ea17e958b9 (Dec 03 2024 - 11:41:08 +0000)
```

Boot options from this screen will install and boot into a standard linux shell. [^buthow]

[^buthow]: Not sure exactly how this goes. TOOD redo this section.