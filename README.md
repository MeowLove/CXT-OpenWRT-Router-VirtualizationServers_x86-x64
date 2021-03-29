<div align="center">
  <a href="https://github.com/MeowLove/OpenWRT-Virtualization-Servers">
      <img src="https://raw.githubusercontent.com/MeowLove/OpenWRT-Virtualization-Servers/master/background/CXT_Logo.png"  >
  </a>
  <h1 align="center">
    OpenWRT-虚拟化-服务器专用 <br>（OpenWRT-Virtualization-Servers）
  </h1>
  <h3 align="center">
    适用于虚拟化服务器和软件路由器的OpenWRT，纯净版本。<br> （OpenWRT(LEDE) for virtualized servers and software routers, pure version.） <br><br>
  </h3>

  <a href="/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg" alt="">
  </a>

  <a href="https://github.com/MeowLove/OpenWRT-Virtualization-Servers/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="">
  </a>
  
  <a href="https://github.com/MeowLove/OpenWRT-Virtualization-Servers/issues/new">
    <img src="https://img.shields.io/badge/Issues-welcome-brightgreen.svg">
  </a>
  
  <a href="https://github.com/MeowLove/OpenWRT-Virtualization-Servers/releases">
    <img src="https://img.shields.io/badge/release-0.3.1-blue.svg?">
  </a>
  
  <a href="https://github.com/MeowLove/OpenWRT-Virtualization-Servers/releases">
    <img src="https://img.shields.io/github/stars/MeowLove/OpenWRT-Virtualization-Servers.svg?style=flat-square&label=Stars&logo=github">
  </a>
  
  <a href="https://github.com/MeowLove/OpenWRT-Virtualization-Servers/">
    <img src="https://img.shields.io/github/forks/MeowLove/OpenWRT-Virtualization-Servers.svg?style=flat-square&label=Forks&logo=github">
  </a>
  
  <a href="https://t.me/Technical_Blog">
    <img src="https://img.shields.io/badge/Contact-telegram-orange">
  </a>
  
</div>
<br>
<div align="center">
  <h3 align="center">
  <hr>
    预览图仅供参考，非最新，一切以成品为准，欢迎大家加入，一起构建更好的系统<br><br>
  </h3>
  <img src="https://raw.githubusercontent.com/MeowLove/OpenWRT-Virtualization-Servers/master/background/Preview_WebUI.png">
  <img src="https://raw.githubusercontent.com/MeowLove/OpenWRT-Virtualization-Servers/master/background/Preview_Function.png">
</div>


## [OpenWRT-虚拟化-服务器专用 （OpenWRT-Virtualization-Servers）](https://github.com/MeowLove/OpenWRT-Virtualization-Servers)<br>

版本跟随 [一键网络重装系统-魔改版](https://www.cxthhhhh.com/network-reinstall-system-modify) 和 [Network-Reinstall-System-Modify](https://github.com/MeowLove/Network-Reinstall-System-Modify) 更新 <br><br>
下载最新【OpenWRT-Virtualization-Servers】镜像：<br>
- 1、https://odc.cxthhhhh.com/
- 2、https://github.com/MeowLove/OpenWRT-Virtualization-Servers/releases/

## 功能：

- 完整的[OpenWRT](https://openwrt.org/) and [LEDE](https://github.com/coolsnowwolf/lede)功能（无富强组件）。
- 完整的IPV6支持，以及DHCPv6支持（支持将宿主机绑定的IPV6分配给虚拟机，支持DUID绑定功能）。 
- 精美的Luci主题[luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)，CXT修改版。（搭配快乐粉和轻量壁纸）
- 大储存空间，支持自由安装软件。（在线安装/Web上传ipk均可）
<br>
<img src="https://raw.githubusercontent.com/MeowLove/OpenWRT-Virtualization-Servers/master/background/Preview_WebLogin.png">
<br>  

- SSH / TTYD终端 / UPnP（通用即插即用）
- 磁盘挂载 / FTP / 文件传输 / Rclone / Samba网络共享
- 计划任务 / 网络监测 / NTP服务器 / uHTTPd / 定时重启
- 带宽监控 / 流量统计 / 上网时间控制 / Turbo ACC 网络加速
- BBR / SFE Fast Path 加速 / DNS加速 / IPv6 加速 / 桥接加速
<br>

- 广告屏蔽大师 Plus+（内网去广告） / WatchCat（断网自动重启）
- 动态 DNS（DDNS IPV4 and IPV6） / 网络唤醒 / KMS服务器
- ZeroTier（内网穿透，便于服务器集群的管理）

## 使用：

- 镜像为虚拟化服务器专用（PVE/VirtualBox/VMware/KVM/XEN/LXC）等x86_64平台使用。
- 多种镜像可供选择（Legacy / UEFI）（ img / qcow2 / vmdk / vdi / bin ）
- 支持定制其他设备镜像，可前往博客[CXT - Enjoy Life | 生活、技术、交友、分享](https://www.cxthhhhh.com/)联系定制。
<br>

- 1、【虚拟机】下载镜像上传到您的宿主机，开虚拟机，将CXT-OpenWRT磁盘导入虚拟机使用。
- 2、【宿主机】服务器可使用[一键网络重装系统-魔改版](https://www.cxthhhhh.com/network-reinstall-system-modify)一键DD，或手动DD到硬盘使用。

## 说明：

- 1、默认WebUI端口：http://[your-set-ip]:2096
- 2、默认账号：root
- 3、默认密码：cxthhhhh.com
- 4、默认Lan口：10.10.1.1 / 255.255.255.0

## 高级说明：

- 1、编辑网络配置 vi /etc/config/network
- 重启网络命令，执行 /etc/init.d/network reload
- 不会配的，可以先本地虚拟机web配置好，导出虚拟机再上传整个虚拟机到云端服务器，再开机即可。
- 2、编辑防火墙配置 vi /etc/config/firewall
- 默认已允许WebUI监听的2096端口的Wan口访问规则
- 开启Wan口外网全部访问放行，将 zone 'wan' 中 input forward 的 'REJECT' 均改为 'ACCEPT'，然后 reboot 重启，即可放行Wan口的流量进出和转发请求。
- 3、编辑Web访问配置 vi /etc/config/uhttpd
- 开启仅允许Lan口访问Web管理页面，将 option rfc1918_filter 从'0' 改为 '1'，重启机器，即生效。
- 4、其他设置，建议WebUI操作。
- 通过以上VNC的Shell操作，正常配置网络，已保证Wan口访问WebUI。
- 5、WebUI登陆后，可修改防火墙放行Wan口所有数据，或执行自己需要的操作。
- 自行安装软件，可通过Web自带的文件传输安装或在线包和软件提供在线库安装任意软件。
- 可挂载额外硬盘做微力同步、BT下载、家庭云盘等，享受一切折腾的快乐~
- 6、为了服务器安全，一些涉及安全的设置（如：实时监控和ttyd终端等），默认不允许wan口访问。请内网lan口访问。
- 不推荐开放这些危险的服务在公网。想要wan口访问此类服务，请自己在WebUI添加防火墙规则，以及在端口转发添加规则即可。
- 7、有DHCPv6客户端发送DUID申请IPV6的服务商，需要开放DHCPv6客户端对应的Wan口防火墙，否则防火墙默认拦截。
- DHCPv6相关端口：客户端使用UDP端口号546，服务器使用端口号547。
- 不会设置端口流量放行的话，就网络-防火墙-入站/出站/转发，所有规则改为ACCEPT接受。
<br>

## 安装自己需要的软件

- 本固件作为基本的OpenWRT框架，允许用户任意安装自己的软件。（相比市面其他固件，具有高达8倍的充足的储存空间）
- 关于OpenWRT安装 XXX 软件，请谷歌搜索关键字“OpenWRT install XXX”，或者百度搜索“OpenWRT 安装 XXX”。这是非常的简单。例如：
- https://www.google.com/search?q=OpenWRT+install+WireGuard
- 大多数软件的官方文档中均有提供安装说明，例如：
- https://openwrt.org/docs/guide-user/services/vpn/wireguard/basics
- 因此，在系统中安装软件这种，极其简单的问题，大家要多发挥自主搜索和解决问题的能力！
<br>


## 常见网络环境 部署简述
<br>

### 宿主机多网卡，多IP
- 最简单的情况，有手就行。Wan口通常DHCP自动获取网络，或VNC手动修改网络配置，绑定好wan和lan，重启即可访问。
<br>

### 宿主机单网口，单/多IP
- 虚拟机建2个网桥，一个绑定外网，一个绑定内网即可。同上，没什么区别。
<br>

### 云服务器（虚拟机），单网口，单IP
- DD安装好镜像后，OpenWRT启动日志停止后，VNC回车修改网络配置 vi /etc/config/network
<br>

#### 云服务器绑定IP到Wan口
- 1、删除 Lan口 配置
- 2、绑定网卡 eth0 到 Wan口，并设置DHCP自动获取。
```
config interface 'wan'
    option ifname 'eth0'
    option proto 'dhcp'
```
- 3、如果你的服务商未提供DHCP，那就配置Wan口静态IP。
```
config interface 'wan'
	option ifname 'eth0'
	option proto 'static'
	option ipaddr 'x.x.x.x'
	option netmask 'x.x.x.x'
	option gateway 'x.x.x.x'
	option dns '1.1.1.1 8.8.8.8 223.5.5.5'
```
- 4、重启网络命令，执行 /etc/init.d/network reload
- 5、成功访问到WebUI后，可以再添加wan6接口（IPV6）。网络配置参考下方官方文档说明：
- OpenWRT官方文档：https://openwrt.org/docs/guide-user/base-system/basic-networking
<br>

#### 云服务器绑定IP到Lan口

- 1、配置Lan口静态IP（动态IP同上Wan配置，不在举例，只是改个接口名字）
```
config interface 'lan'
	option type 'bridge'
	option ifname 'eth0'
	option proto 'static'
	option ipaddr 'x.x.x.x'
	option netmask 'x.x.x.x'
	option gateway 'x.x.x.x'
	option dns '1.1.1.1 8.8.8.8 223.5.5.5'
```
- 3、重启网络命令，执行 /etc/init.d/network reload
- 4、成功访问到WebUI后，可以再添加wan6接口（IPV6）。网络配置参考下方官方文档说明：
- OpenWRT官方文档：https://openwrt.org/docs/guide-user/base-system/basic-networking
- 5、记得关闭OpenWRT在Lan口自带的DHCP服务功能。因为在Lan口，会和商家DHCP服务器冲突，网络异常。
- 一个子网环境，只能容纳一个DHCP服务器。因此不关闭Lan口DHCP服务，有可能被视为你攻击商家网络，严格的商家可能视为你违约，封号处理。
- Dnsmasq设置忽略向Lan口提供DHCP服务
```
uci set dhcp.lan.ignore="1"
uci commit dhcp
/etc/init.d/dnsmasq restart
/etc/init.d/odhcpd restart
```
- DNS and DHCP官方文档：https://openwrt.org/docs/guide-user/base-system/dhcp_configuration#disabling_dhcp_role
<br>

### 云服务器（虚拟机），多网口，多IP
- 同宿主机，不再展开
<br>

## [CXT - Enjoy Life | 生活、技术、交友、分享](https://www.cxthhhhh.com/)

- [CXT 社区 | OpenWRT 玩家](https://bbs.cxthhhhh.com)
- [Telegram 组群 Technical Blog | 技術博客](https://t.me/Technical_Blog)
- [Telegram 频道 My Share](https://t.me/me_share)
<br>

## CXT社区-软路由众筹交流
- 点击链接加入群聊【CXT社区-软路由众筹交流】QQ群【708471105】：
- https://jq.qq.com/?_wv=1027&k=WDoacIbd
<img src="https://raw.githubusercontent.com/MeowLove/OpenWRT-Virtualization-Servers/master/background/CXT-Router-Group-2021.png">
<br>

## 再次感谢

- 没有以下的项目的支持，就没有【OpenWRT-虚拟化-服务器专用（OpenWRT-Virtualization-Servers）】的诞生。
- 技术支持：[CXT - Enjoy Life | 生活、技术、交友、分享](https://www.cxthhhhh.com/)
- [一键网络重装系统-魔改版](https://www.cxthhhhh.com/network-reinstall-system-modify)
- [MeowLove/Network-Reinstall-System-Modify](https://github.com/MeowLove/Network-Reinstall-System-Modify)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt/)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

