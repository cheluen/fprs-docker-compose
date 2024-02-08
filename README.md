# fprs-docker-compose-
使用docker-compose一键部署frps服务端
部署前记得修改frps.toml文件
[common]
bind_port = 4000 
bind_addr = ip #ip换成真实ip
token = token #token换成自定义的密码
vhost_http_port = 80
dashboard_port = 29999 #面板通讯端口
dashboard_user = user #面板用户名
dashboard_pwd = pwd #面板密码

修改完成后使用docker-compose一键部署
原项目链接:https://github.com/fatedier/frp
