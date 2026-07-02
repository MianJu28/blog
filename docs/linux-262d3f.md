---
title: Linux
date: '2026-07-02 14:33:41'
head: []
outline: deep
sidebar: false
prev: false
next: false
---



# Linux

## Linux

### 添加环境变量

```sh
vim ~/.bashrc # /etc/profile 或 /etc/environment

export PATH="$PATH:/path/to/bin"

source ~/.bashrc
```

### 解决端口占用

```sh
sudo ss -tulnp | grep <port> # 查询端口
ps -ef | grep <name> # 查询进程名
sudo kill [-9] <pid>
```
