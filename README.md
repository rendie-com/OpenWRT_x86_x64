# OpenWRT_x86_x64
OpenWRT 安装说明

写盘工具：https://github.com/balena-io/etcher/releases  (注：该软件不能在winPE中运行,该软件可以把openwrt写到U盘中，也可以写到硬盘中)

固件下载地址：https://github.com/DHDAXCW/OpenWRT_x86_x64/releases

注：就是把openWRT写入到另一个盘中（必须是一整个硬盘，不是一某个分区），和装系统一样。

命令：

输入：vi /etc/config/network

输入：i

找到 192.168.11.1  改成自己局域网的IP,如：10.192.168.1.11（目的是为了做旁路由）

按下：esc键

输入：【:wq】保存

输入：【reboot】重启

然后在另一台电脑，的浏览器中输入你刚刚修改的IP，如：10.192.168.1.11  ，如果能打开说明openWRT安装成功。

用户名：root 密码：password  管理IP：10.192.168.1.11

关机命令:poweroff

=========================================================================================

第二种：在Windows中安装OpenWRT（用 hyper-v 虚拟机）

windows 11 需要专业版

[win11系统第一次开机跳过联网的办法](https://zhuanlan.zhihu.com/p/583640911?utm_id=0)

[【保姆级】软路由小主机安装Windows，hyper-v，爱快iKuai，OpenWrt，NAS等等，打造all in one 小主机，让你的小主机好玩又好用！（CC字幕）](https://www.youtube.com/watch?v=wLUvwSSZ0Us)---从37钟的位置开始看。
