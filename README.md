# Replit_Root
Replit获取root权限
wget https://fh168.fra1.cdn.digitaloceanspaces.com/yt.zip   （需要回车一次）


unzip yt.zip （需要回车一次）

unzip root.zip

tar -xvf root.tar.xz

./dist/proot -S . /bin/bash

su
拓展命令行：

更改root密码
passwd

安装sudo命令
apt-get install sudo

安装wget命令
apt-get update -y && apt-get install -y wget

安装curl命令
apt-get update -y && apt-get install curl -y

查看系统版本
cat /etc/issue
