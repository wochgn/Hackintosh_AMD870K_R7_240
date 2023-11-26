# Hackintosh_AMD870K_R7_240
OpenCore EFI Files for AMD Athlon X4 870K &amp; Radeon R7 240. Tested on macOS Catalina 10.15.7.

# Specs
* CPU: AMD Athlon X4 870K
* RAM: 8GB 1600MHz DDR3
* Motherboard: Gigabyte GA-F2A88XM-DS2-TM
* GPU: Radeon R7 240 2G GDDR5
* NIC: Realtek RTL8111
* Audio: Realtek ALC887

# What's working
* Ethernet(Realtek RTL8111)
* Audio(Realtek ALC887, but with `VoodooHDA.kext`)
* USB(WIP, only USB2 ports work)
* GPU(Radeon R7 240(with hardware ID`6613:1002`), With QE/CI & Metal, but Hardware decoding dosen't work)

# What's not working
* Sleep(Haven't worked on patching this yet)
* USB3(Maybe my `USBPorts.kext` was configured incorrectly)

# Bugs
* Music stream platforms like Netease Cloud Music or KuGou would crash when trying to play music.
