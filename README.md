# Build hanwckf's immortalwrt-mt798x

[Source code](https://github.com/hanwckf/immortalwrt-mt798x)

[immortalwrt-mt798x project introduction](https://cmi.hanwckf.top/p/immortalwrt-mt798x)

* Based on immortalwrt 21.02 branch, kernel version 5.4, currently only supports mt7981/mt7986
* Use the wired driver, hnat driver, kernel patch and configuration tools provided by mtk-openwrt-feeds to support all hardware acceleration features
* Both mt7981/mt7986 support two PPEs, each PPE has 32k Entry (when the wired driver uses ADMAv1, each PPE supports a maximum of 16k Entry)
* Use mtwifi original wireless driver (currently using version 7.6.6.1 by default), turn on 802.11k by default, and support all acceleration features including warp
* The newly developed mtwifi-cfg wireless configuration tool supports openwrt's native luci interface and netifd-wireless standard interface. In addition, it also supports luci-app-mtk and wifi-profile provided by the original mtk factory.

This repository supported models

+ CMCC RAX3000M , MT7981 , 512MB RAM , 128MB spi-nand ROM , AX3000 , USB , 4*1Gbe.
