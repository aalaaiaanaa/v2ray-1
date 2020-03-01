# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本

## 脚本说明
[V2Ray 一键安装脚本](https://github.com/233boy/v2ray/wiki/V2Ray%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85%E8%84%9A%E6%9C%AC)

## 搭建教程
[V2Ray搭建详细图文教程](https://github.com/233boy/v2ray/wiki/V2Ray%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E5%9B%BE%E6%96%87%E6%95%99%E7%A8%8B)

## 资助 V2Ray
请考虑 [资助 V2Ray 发展](https://www.v2ray.com/chapter_00/02_donate.html)

## 更多 V2Ray 教程文章
https://github.com/233boy/v2ray/wiki



# https://github.com/Crownzhu/v2ray_SS--GCP
# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本  

安装或卸载  
要求：Ubuntu 14+ / Debian 7+ / CentOS 7+ 系统的小鸡鸡  
推荐使用 Debian 9 系统，脚本会自动启用 BBR 优化。  
1. 使用命令sudo -i取得root权限  
2. 使用 root 用户输入下面命令安装或卸载  
```javascript
git clone https://github.com/Crownzhu/v2ray_SS--GCP
cd v2ray_SS--GoogleCloud
chmod +x install.sh
./install.sh local
```
如果提示 git 命令不可用，则使用 root 用户输入下面命令安装或卸载  
`bash <(curl -s -L https://git.io/v2ray.sh)`
<br>
<br>
## 另附： 
SSR 一键安装脚本（四合一）-by 秋水逸冰  
```javascript
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```
卸载方法<br>
./shadowsocks-all.sh uninstall<br>
启动/停止/重启/查看状态（ShadowsocksR版）：<br> 
/etc/init.d/shadowsocks-r start/stop/restart/status   
