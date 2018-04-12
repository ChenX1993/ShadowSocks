# VPN
Alibaba cloud + ShadowSocks

SSH远程访问
sh -i keys/SSH.pem root@47.98.171.94

配置ShadowSocks：
参照秋水伊冰的手册，https://teddysun.com/486.html

主要问题：
阿里云安全规则tcp需要添加ShadowSocks所使用的端口号，具体为端口号/端口号
关闭阿里云防火墙
