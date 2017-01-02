# patches_openwrt
Patches for OpenWrt

## internet_radio subdir
Patches for creating an internet/wifi radio using an embedded router and openwrt
- customfeeds.tar.gz
  - openwrt custom feeds of old versions of mpd and mpc packages (working more reliably than current versions)
- customfeeds_*.diff
  - rename packages to reflect old versions
- trunk_*.diff
  - add device usb support and custom feeds for internet radio to openwrt
- trunk_*.config
  - enable custom packages for building openwrt
