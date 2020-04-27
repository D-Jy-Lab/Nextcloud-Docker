# Nextcloud-Docker
Nextcloud Docker 添加Cron SMB以及常用支持。

https://hub.docker.com/repository/docker/duan2001/nextcloud


docker run -d --restart=always --name nextcloud -p 8080:80 -v F:\Nextcloud:/var/www/html  duan2001/nextcloud:latest
