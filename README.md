# wire-guard-one-key-install

wireguard one-keyinstall for debian 8+

一键命令Usage:

wget --no-check-certificate -qO- 'https://github.com/rockyzhng/wire-guard-one-key-install/blob/master/wireguard.sh'| bash

关闭命令Shutdown: wg-quick down wg0

启动命令Start: wg-quick up wg0

服务端配置文件server config: /etc/wireguard/wg0.conf

客户端配置文件client config: /etc/wireguard/wg0-client.conf
