![Logo](https://raw.githubusercontent.com/neodevpro/neodevhost/master/logo.png)

    
    
    
## The Powerful Friendly Uptodate AD Blocking Hosts 最新强大而友善的去广告


[![Build Status](https://img.shields.io/github/workflow/status/neodevpro/neodevhost/CI/master)](https://github.com/neodevpro/neodevhost/actions?workflow=CI)<br/>
[![Last commit](https://img.shields.io/github/last-commit/neodevpro/neodevhost.svg)](https://github.com/neodevpro/neodevhost/commit/master)<br/>
[![license](https://img.shields.io/github/license/neodevpro/neodevhost.svg)](https://github.com/neodevpro/neodevhost/blob/master/LICENSE)

```
Total ad / tracking block list 屏蔽追踪广告总数: 100796

Total allowlist list 允许名单总数: 1564

Total combine list 结合总数： 100665

Update 更新时间: 2020-08-08
```
### UPTODATE 保持最新<br/>
    Merge everyhours　每小时更新
### POWERFUL　 强大有效<br/>
    To block all ad / tracking  有效拦截广告追踪　
### FRIENDLY　友善使用<br/>
    Easy to use and welcome to report issues　简单使用欢迎回报问题

## Supported Platform 支持平台

```
-Windows
-Android
-Linux
-Mac OS
-Openwrt
-etc
```
### Supported adblocker 广告拦截器
```
-Pihole
-Adaway
-Adblocker/Adguard
-etc
```

## Download 下载 

Format 格式 | Compatible with 适用于 | Raw | 国内加速链接  
--------- |:-------------:|:-------------:|:-------------:
Host | Pihole，Adaway，hBlock ... |[link](https://raw.githubusercontent.com/neodevpro/neodevhost/master/host) | [link](https://cdn.jsdelivr.net/gh/neodevpro/neodevhost@latest/host)
Adblocker | uBlock，Adguard ... |[link](https://raw.githubusercontent.com/neodevpro/neodevhost/master/adblocker) | [link](https://cdn.jsdelivr.net/gh/neodevpro/neodevhost@latest/adblocker) 
Dnsmasq | Dns ... |[link](https://raw.githubusercontent.com/neodevpro/neodevhost/master/host_dnsmasq.conf) | [link](https://cdn.jsdelivr.net/gh/neodevpro/neodevhost@latest/host_dnsmasq.conf)

## How To Use 如何使用
```
1.Download both files/copy link of files
2.Add host and whitelist file/link into adblocker
3.Update the data source in the app
```
```
1.下载两个文件/复制下载链接
2.添加文件或者下载链接到广告拦截器
3.更新数据规则
```
## Pihole Installation 安装导入教程

Import and Installation 导入和安装<br/>

1.Login to pihole website<br/>
2.Go to Groupmanagement > Adlists<br/>
3.copy the NEODEV AD host link into "Address:"<br/>
4.open terminal<br/>
5. Run the following command :<br/>
```
sudo -i
sudo curl -s https://raw.githubusercontent.com/neodevpro/neodevhost/master/install.sh | bash
pihole -g
```
6.Wait for 20 mins around  <br/>
7.Then it will import both NEODEV host and whitelist into your Pihole <br/>


Remove and Uninstall 移除和卸载<br/>

1.Login to pihole website<br/>
2.Go to Groupmanagement > Adlists<br/>
3.click the red trash can button<br/>
4.open terminal<br/>
5. Run the following command :<br/>
```
sudo -i
sudo curl -s https://raw.githubusercontent.com/neodevpro/neodevhost/master/uninstall.sh | bash
pihole -g
```
6.Wait for 20 mins around  <br/> <br/>
7.Then it will Remove and Uninstall both NEODEV host and whitelist from your Pihole <br/>

## Sources of AD-hosts data 去广告host源
AD-hostss | Link  
--------- |:-------------:
Ad-wars | [link](https://raw.githubusercontent.com/jdlingyu/ad-wars/master/hosts)
Adguard | [link](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)
Anti-AD | [link](https://raw.githubusercontent.com/privacy-protection-tools/anti-AD/master/anti-ad-domains.txt)
Neohost | [link](https://hosts.nfz.moe/full/hosts)
StevenBlack | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling/hosts)
Yhosts | [link](https://raw.githubusercontent.com/VeleSila/yhosts/master/hosts)

## Sources of Allowlist 允许名单
Allowlist | Link  
--------- |:-------------:
AnudeepND | [link](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/whitelist.txt)
AnudeepND-optional | [link](https://raw.githubusercontent.com/anudeepND/whitelist/master/domains/optional-list.txt)
Ultimate-Hosts-Blacklist | [link](https://raw.githubusercontent.com/Ultimate-Hosts-Blacklist/whitelist/master/domains.list)
WildcardTech | [link](https://raw.githubusercontent.com/WildcardTech/Filter-Domain-List/master/whitelist.txt)
Yhosts | [link](https://raw.githubusercontent.com/VeleSila/yhosts/master/whitelist.txt)
