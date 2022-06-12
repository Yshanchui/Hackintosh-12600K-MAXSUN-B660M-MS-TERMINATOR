# Hackintosh-12600K-MAXSUN-B660M-MS-TERMINATOR

# 2022年6月12日更新
升级oc至0.8.1 
更新intel wifi 蓝牙驱动 支持AX210
更新独显驱动
可升级

# 2022年5月16日更新

修正内置扬声器，可正常使用内置扬声器
调整睡眠，可正常睡眠唤醒
可正常更新至12.4版本

#
适用于 12600K + 铭瑄B660M终结者 DDR4 黑苹果引导文件

基于 OpenCore 0.7.9 版本，机型 MacPro 7,1，系统 MacOS 12.3

ACHI usb定制


# 本机配置

| 配置        | 型号                      |
|-----------|-------------------------|
| CPU       | intel i5 12600K         |
| 主板        | 铭瑄 b660m 终结者            |
| 显卡        | 6600xt 8g               |
| 内存        | 威刚 4000MHz 8G * 2       |
| SSD       | 三星 pm9a1                |
| WiFi + 蓝牙 | BCM94360CD (PCI+USB转接卡) |

![avatar](png.jpg)

# 使用情况
装配intel wifi 蓝牙 kext文件 ，默认未启用。intel网卡启用即可

# BIOS 配置


### 禁用：

基本上默认 bios都是关的
serial port 可以关
### 开启：
基本上默认 bios都是开的
xmp自己调整
VT-x要自己开启
