# 科学上网指南

> 此指南为复制网上的教程，为了防止以后教程连接不见做得记录，原文连接[https://www.i5seo.com/mac-build-shadowsocksr-ssr.html](https://www.i5seo.com/mac-build-shadowsocksr-ssr.html)

## 1. 购买国外服务器

推荐 [vultr](https://www.vultr.com/)

[端口检测工具](http://coolaf.com/tool/port)

## 2. 连接服务器搭建ssr

### 2.1 连接服务器

```
ssh root@ip
```

### 2.2 搭建SSR

```
yum update -y

yum install unzip zip -y

yum install wget -y

wget -N –no-check-certificate https://raw.githubusercontent.com/Moexin/Easy-SSR-Bash-Python-The-Final/master/ssr.zip

unzip ssr.zip

cd SSR*

bash install.sh
```

### 2.3 安装bbr加速

```
wget https://github.com/teddysun/across/raw/master/bbr.sh

chmod +x bbr.sh

./bbr.sh
```

## 3 ssr用户管理

输入ssr即可


## 最后下载小飞机设置服务器就行了
