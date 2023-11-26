# Hackintosh_AMD870K_R7_240
OpenCore EFI Files for AMD Athlon X4 870K & Radeon R7 240. macOS Catalina 10.15.7测试通过
# 配置
* CPU: AMD Athlon X4 870K
* RAM: 8GB 1600MHz DDR3
* Motherboard: Gigabyte GA-F2A88XM-DS2-TM
* GPU: Radeon R7 240 2G GDDR5
* NIC: Realtek RTL8111
* Audio: Realtek ALC887

# What's working
* 有线网(Realtek RTL8111)
* 音频(Realtek ALC887, 但是用的`VoodooHDA.kext`)
* USB(WIP, only USB2 ports work)
* 显卡(Radeon R7 240(硬件ID 6613:1002), QE/CI & Metal工作, 但硬件解码不工作，猜想和没有核显有关)

# What's not working
* 睡眠 ~~没搞（~~
* USB3(或许是没定制好)

# Bugs
* 不知道为啥网易云酷狗这类音乐软件一点播放就闪退
