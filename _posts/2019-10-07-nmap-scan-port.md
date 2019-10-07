---
layout: post
title: Nmap列举远程机器开放端口
date: 2019-10-07 18:03
homepage: https://litterB.github.io
author: LitterB
thumbnail: nmap.jpg
---
#### 基础命令
1. nmap www.baidu.com 基础的端口扫描指令
2. nmap -Pn www.baidu.com 防防火墙
3. nmap -p 1-1000 www.baidu.com 指定扫描1-1000的端口
4. nmap --dns-server 8.8.8.8 www.baidu.com 指定dns解析