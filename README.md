# wire-guard-one-key-install

wireguard one-key install for debian 8+

一键命令Usage:

wget --no-check-certificate -qO- 'https://github.com/rockyzhng/wireguard-one-key-install-for-Debian/raw/master/wireguard.sh'| bash

默认端口default port: 51820

关闭命令shutdown: wg-quick down wg0

启动命令start: wg-quick up wg0

服务端配置文件server config: /etc/wireguard/wg0.conf

客户端配置文件client config: /etc/wireguard/wg0-client.conf
