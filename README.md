## Xware

- 固件命名结构： Xware 版本号\_（cpu 架构\_指令集\_c 库类型｜产品名称）.zip

### 说明

1. Xware 指 迅雷固件代号
2. CPU架构 指 CPU类型和大小端（l 小、b大）
3. 指令集 指 CPU 的指令集，如 v5te、v5t、603e 等
4. 产品名称 指 如果有产品名称则指该产品专用，专用不再在版本名称体现 CPU 构架与指令集
5. 如果没有产品名称则表示在该 CPU 架构下通用

### 支持列表

| **产品型号**                     | **系统固件**                                 | **CPU信息**                                | **xware 版本**                      |
| ---------------------------- | ---------------------------------------- | ---------------------------------------- | --------------------------------- |
| 华硕 ASUS 500 GP V1            | tomato DualWAN                           | Broadcom BCM4704 chip rev 9 pkg 0        | xware_mipsel_32_uclibc            |
| Buffalo Linkstation          |                                          | ARMv6-compatible processor rev 5(v61)    | xware_armel_v5te_glibc            |
| buffalo ls421de              |                                          | Atheros AR9344 rev 2                     | xware_armel_v5te_glibc            |
| HuaWei HG255D                | openwrt                                  | Ralink RT3052 id:1 rev:3 MIPS 24Kc V4.12 | xware_mipsel_32_uclibc            |
| Iomega Cloud Edition         |                                          |                                          | xware_iomega_cloud                |
| my book live                 |                                          | APM82181                                 | xware_my_book_live                |
| MyBookLive 1TB               | Debian Wheezy 7.1                        | APM82181                                 | xware_my_book_live                |
| NW762                        |                                          |                                          | xware_mipsel_32_uclibc            |
| qnap arm                     |                                          | ARMv5te                                  | xware_armel_v5te_glibc            |
| TP-LINK TL-MR3420            | openwrt                                  | Atheros AR7241 rev 1 MIPS 24kc v7.4      | xware_mipseb_32_uclibc            |
| TP-LINK TL-WR741ND v4        | openwrt                                  | Atheros AR9330 rev 1 MIPS 24Kc V7.4      | xware_mipseb_32_uclibc            |
| TP-LINK TL-WR941ND           |                                          | Atheros AR9132 MIPS 24Kc v7.4            | xware_mipseb_32_uclibc            |
| X86                          |                                          |                                          | xware_x86_32_glibc                |
| 巴法络AG300H                    | dd-wrt                                   | Atheros AR7161 rev 2(0xaa) MIPS 24Kc V7.4 | xware_mipseb_32_uclibc            |
| 烽火hg320                      | tt                                       | Broadcom BCM5357 chip rev 2 pkg 9 MIPS 74K V4.9 | xware_mipsel_32_uclibc            |
| 泡泡1                          |                                          |                                          | xware_armel_v5te_glibc            |
| HG320                        | tt                                       | MIPS 74K V4.9                            | xware xware_mipsel_32_uclibc      |
| 水星 MW4530                    | Openwrt                                  | Atheros AR9344 rev 2                     | xware_mipseb_32_uclibc            |
| 群晖 713+                      | DSM                                      | Intel Atom                               | xware_x86_32_glibc                |
| 华硕 ASUS RT-AC56U             | Asuswrt-Merin                            | BCM4708                                  | xware_asus_rt_ac56u               |
| MyBookLive 1TB               | Debian Wheezy 7.1                        | APM82181                                 | xware_my_book_live                |
| HG320                        | tt                                       | MIPS 74K V4.9 xware1.01                  | xware_mipsel_32_uclibc            |
| 华为HG556a                     | openwrt  xware                           | bcm63xx/HW556_B (0x6358/0xA1)            | xware_mipseb_32_uclibc            |
| 水星 MW4530                    | Openwrt                                  | Atheros AR9344 rev 2                     | xware_mipseb_32_uclibc            |
| 华硕 ASUS RT-AC56U             | OS：Asuswrt-Merin                         | Broadcom 4708                            | xware_asus_rt_ac56u               |
| 黑群晖DSM5.0Bet                 | DSM_DS3612xs_4418                        | N70E-DR V2  Intel® Celeron® Processor 1037U | Xware1.0.10_x86_32_glibc          |
| 普通X86 PC平台                   | 黑群辉 DSM4.2                               | cpu PD915                                | xware_x86_32_glibc                |
| X86 PC平台                     | ESXI下安装  黑裙 DSM4.2（是通过直通阵列卡挂载的硬盘）        | Inte（R） xeon®CPU E31265L @2.4GHz         | xware_x86_32_glibc                |
| 华硕 ASUS RT-N16               | tomato                                   | Broadcom BCM4716                         | xware_mipsel_32_uclibc            |
| MCS4 2Bay                    | MCS                                      | APM80186                                 | xware_my_book_live                |
| 华硕 ASUS ac68u                | DD-WRT                                   | Broadcom 4708                            | xware_armel_v5te_glibc            |
| Buffalo LinkStation LS-WVL/E | Buffalo 官方版固件                            | Feroceon 88FR131 rev 1 (v5l)             | Xware1.0.22_armel_v5te_glibc      |
| 群晖DS213+                     | DSM 4.3-3810 Update 2                    | Freescale QorIQ P1022                    | xware_my_book_live                |
| RE200E-CA                    | Tomato                                   | Broadcom BCM5357 chip rev 1 pkg 9        | xware_my_book_live                |
| cubieboard2                  | Linux Cubian 3.4.67+                     | ARMv7 Processor rev 4 (v7l)              | xware_armel_v5te_glibc            |
| Cubieboard3                  | cubian                                   | ARMv7 processor rer 4 (v71)              | xware_cubieboard                  |
| 如意云RY-1                      | OPENWRT                                  | MIPS 24KEc V5.0                          | xware_mipsel_32_uclibc            |
| 树莓派CPUINFO                   | Linux raspberrypi 3.10.24+               | ARMv6-compatible processor rev 7 (v6l)   | xware_armel_v5te_glibc            |
| 安卓平板                         | Andriod                                  | ARMv6-compatible processor rev 5 (v6l)   | xware_armel_v5te_android          |
| cubieboard                   |                                          | ARMv7 Processor rev 2 (v7l)              | xware_cubieboard                  |
| netgear_6300v2               | dd-wrt-SP2                               | ARMv7 processor rev（v7l）                 | xware_netgear_6300v2              |
| TP-LINK TL-WR703N v1         | OpenWrt 703N                             | Atheros AR9330 rev 1                     | Xware1.0.3_mipseb_32.zip          |
| 西数 my cloud                  |                                          |                                          | xware_armel_v5te_glibc            |
| beaglebone                   | ubuntu12.04                              | am335x/cortxA8                           | 1.0.4_cubieboard                  |
| 群晖DS412+                     | DSM 4.3-3810 Update 3                    | Intel(R) Atom(TM) CPU D2701   @ 2.13GHz  | Xware1.0.4 X86                    |
| 自攒Linux NAS                  | AMD Athlon II x4 605e @ AMD 780G+SB710   | AMD Athlon(tm) II  X4 605e Processor     | Xware1.0.3_x86_32稳定版              |
| 中兴H118N                      | openwrt                                  |                                          | Xware1.0.3_mipsel                 |
| DualWan 520W                 | Tomato v13.09.0042                       | Broadcom BCM5357 chip rev 2  pkg 8       | Xware1.0.4_mipsel_32.zip          |
| atom 230                     | Debian 7                                 |                                          | Xware1.0.1_x86_32                 |
| 开博尔K660I                     | 3099diy固件11.7版                           | realtek 118                              | Xware1.0.4_mipsel_32.zip          |
| Synology 群晖 DS211J           | DSM4.3                                   | Feroceon 88FR131 rev 1 (v5l)             | Xware1.0.4_armel_v5te             |
| DS212                        | DSM4.3-3810 update 3                     | Feroceon 88FR131 rev 1 (v5l)             | Xware1.0.5_armel_v5te_glibc       |
| cubiboard2双卡版                | openwrt for sunxi                        | ARMv7 Processor rev 4 (v7l)              | Xware1.0.23_armel_v5t_uclibc      |
| NetGear WNDR4300             | DD-WRT v24-sp2 (05/27/14) std            | Atheros AR9344 rev 1.2                   | Xware1.0.20_mipseb_32_uclibc.     |
| 华为HG522-c                    | openwrt                                  | Broadcom BCM6358 V1.0                    | Xware1.0.17_mipseb_32_uclibc      |
| TP Link TL-WDR4300（N750）     | DD-WRT v24-sp2 (05/27/14)                | Atheros AR9344 rev 1.2MIPS 74Kc V4.14    | Xware1.0.19_mipseb_32_uclib       |
| NetGear r6300 V1             | DD-WRT Kong Build                        | Broadcom BCM5300 chip rev 1              | Xware1.0.16_mipsel_32_uclibc      |
| 华硕 ASUS RT-N16               | ASUSWRT Merlin 374.41                    | Broadcom BCM4716                         | Xware1.0.16_mipsel_32_uclibc      |
| PcDuino Ver 1版               | ubuntu 内核3.4.29                          | ARMv7 Processor rev 2 (v7l)              | Xware1.0.14_cubieboard            |
| 群晖DS110j                     | DSM5.0-4458 update1                      | Marvell Kirkwood mv6281 ARMv5TE          | Xware1.0.14_armel_v5te_glibc      |
| rg100-aa                     | openwrt                                  | Broadcom BCM6358                         | Xware1.0.12_mipseb_32_uclibc      |
| Buffalo WZR-600DHP2          | DD-WRT V24SP2(23720)                     | ARMv7 Processor rev 0 (v7l)              | Xware1.0.12_netgear_6300v2        |
| 网件(Netgear) WNDR3400V2       | DD-WRT(DD-WRT v24-sp2 (02/26/13) mega    | Broadcom BCM5357 chip rev 2              | Xware1.0.11_mipsel_32_uclibc      |
| 网件(Netgear) WNDR4500         | DD-WRT                                   | Broadcom BCM5300 chip rev 1              | Xware1.0.12_mipsel_32_uclibc      |
| 华硕 ASUS N13U-B1              | openwrt                                  | Ralink RT3052 id:1 rev:3                 | Xware1.0.12 xware_mipsel_32       |
| 群晖DS214se                    | DSM 5.0-4458                             | Marvell PJ4Bv7 Processor rev 1 (v7l)     | Xware1.0.11_armel_v5te_glibc      |
| Netgear R7000                | DD-WRT Kongar 23720                      | ARMv7 Processor rev 0 (v7l)              | Xware: Xware1.0.11_netgear_6300v2 |
| 小度路由 ai-br100                | Base on OpenWrt (PandoraBox, r212)       | MediaTek MT7620A                         | xware_mipsel_32_uclibc            |
| 群晖 DS214+                    | DSM 5.0-4458                             | Marvell PJ4Bv7 Processor rev 2 (v7l)     | Xware 1.0.11_cubieboard           |
| QNAP TS 109 II               | Linux version 2.6.12.6-arm1              | ARM926EJ-Sid(wb) rev 0 (v5l)             | Xware1.0.7_armel_v5te_glibc       |
| QNAP 269L                    | QTS4.0.3                                 | Intel(R) Atom(TM) CPU D2701              | Xware1.0.10_x86_32_glibc          |
| 水星 MW300R                    | Openwrt                                  | Atheros AR9341 rev 2                     | Xware 1.0.1_mipsb_32              |
| 群晖 DS112                     | DSM5.0                                   | MARVELL Kirkwood 1.6 GHz                 | Xware1.0.8_armel_v5te_glibc       |
| 极路由1 HC6361                  | HiWiFi官方                                 | Atheros AR9330 rev 1                     | Xware1.0.30_mipseb_32_uclibc.zip  |
| Beaglebone Black Rev C       | Official Debian 7.5 for Beaglebone Black | ARMv7 Processor rev 2 (v7l)              | Xware1.0.27_cubieboard.zip        |
| ChinaNet RG200E-CA           | Tomato 1.28.0121                         | Broadcom BCM5357 chip rev 1 pkg 9        | Xware1.0.31_mipsel_32_uclibc.zip  |
| Netgear WNDR3700 v2          | DD-WRT                                   | Atheros AR7161 rev 2                     | Xware1.0.31_mipseb_32_uclibc.zip  |
| 群晖214                        | 官方                                       | /                                        | Xware1.0.31_armel_v5te_glibc.zip  |

### 安装方法

以 Xware1.0.31\_mipsel\_32\_uclibc.zip 安装在 MT7620 上为例

1. 解压 Xware1.0.31\_mipsel\_32\_uclibc.zip 压缩包，发现只有 4 个文件
2. 将这四个文件通过 WinSCP 都复制到路由器下
3. putty 登录，切换目录到存放上边四个文的目录，执行下边的命令

```
chmod 777 *
./portal
```
执行行完出现下边这段信息    
```
ETMDaemon            portal
EmbedThunderManager  vod_httpserver
[root@xiazaibao:/xl]#chmod 777 *
[root@xiazaibao:/xl]#./portal
initing...
try stopping xunlei service first...
killall: ETMDaemon: no process killed
killall: EmbedThunderManager: no process killed
killall: vod_httpserver: no process killed
setting xunlei runtime env...
bind(3): errno = 125.
port: 9001 is usable.

YOUR CONTROL PORT IS: 9001

starting xunlei service...
etm path: /xl
execv: /xl/lib/ETMDaemon.

getting xunlei service info...
Connecting to 127.0.0.1:9001 (127.0.0.1:9001)
the active key is not valid.

try again...(has tried 1 time(s)).
getting xunlei service info...
Connecting to 127.0.0.1:9001 (127.0.0.1:9001)

THE ACTIVE CODE IS: fkpswf

go to http://yuancheng.xunlei.com, bind your device with the active code.
finished.
```
看到上面的 ```THE ACTIVE CODE IS: fkpswf``` 

得到这个 code 就可以去 [http://yuancheng.xunlei.com](http://yuancheng.xunlei.com)  绑定这个设备了

![Bind](images/bind.png?raw=true "Bind")

绑定成功就可以愉快的享受远程下载了。

绑定成功后停止服务命令：

```
./portal -s
```

开启服务的命令：

```
./portal
```
### 查看当前信息

首先，启动远程服务，找到你的设备IP，在浏览器里输入以下地址，host 换成你设备的 IP 

```http://host:9000/getsysinfo```

从返回的结果中，找到6位数的激活码

*若是威联通的请用 9001 端口，若是小米盒子和电视请用 19000 端口，其他的用 9000 端口*

举个例子：

我的路由器 IP 是 192.168.111.1，端口是 9000，即在浏览器输入：

[http://192.168.111.1:9000/getsysinfo](http://192.168.111.1:9000/getsysinfo)

![Sysinfo](images/sysinfo.png?raw=true "Sysinfo")

返回结果对应说明：

```
[result, is_net_ok, is_license_ok, is_bind_ok, "bind_acktive_key", is_disk_ok, "version", "user_name", is_ever_binded, userid, vip_level]
```

* result: 0 表示返回结果成功
* is_net_ok:  1 表示检测网络正常，0 表示检测网络异常
* is_license_ok: 1 表示 license 检测通过，0 表示 license 检测不通过
* is_bind_ok: 1 表示已绑定成功，0 表示未绑定
* bind_acktive_key: 此字符串为绑定 key，在未绑定的情况下，会返回绑定的 key；已绑定成功时，或返回空
* is_disk_ok: 1 表示磁盘挂载检测成功，0 表示磁盘挂载检测失败
* version: 目前运行的迅雷库版本
* user_name: 如果已绑定，返回绑定的用户名，否则返回为空
* is_ever_binded: 如果曾经绑定，则为 1，从未绑定过则为 0，一般在网络断开时检查此字段判断是否可以查看任务列表
* userid: 绑定的迅雷会员 ID
* vip_leve: 绑定的迅雷会员等级


若 http://host:9000/getsysinfo 在浏览器无法打开，说明远程服务未启动。

若打开后 ```is_license_ok=0```，即检测不通过，说明 license 过期了或非法或遭封杀！

### 解除绑定

```
http://host:9000/unbind
```

host 换成你设备的 IP

若返回结果为[0]，则解绑成功，否则不成功！