2016-07-09

加入了Mysql 集群监控

zabbix agent 监控mysql用户 从ZBBBIX_USER 修改为  ZABBIX_CHECK_USER 

修复了 rabbitmq  主机名跟节点名不对应， parations not found（要求/etc/host中有当前主机名解析）

加入elasticearch 2.x 监控支持

haproxy 监控 需要线下部署包挂载 /var/run/haproxy 目录（这个目录下为haproxy 的socket 文件）

zabbix  线下安装agent 的 offlineshurenyunrepo

  centos7 repo 添加依赖包 socat-1.7.2.2-5.el7.x86_64.rpm python-backports-ssl_match_hostname-3.4.0.2-4.el7.noarch.rpm  python-backports-1.0-8.el7.x86_64.rpm 

  ubuntu14.04 repo 添加依赖包 socat_1.7.2.3-1_amd64.deb