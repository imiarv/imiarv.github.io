---
title: "Linux Deploy 安装教程"
layout: post
date: 2024-01-14
post-image: "https://raw.githubusercontent.com/imiarv/imiarv.github.io/website-update/assets/images/Linux%20Deploy%20%E5%AE%89%E8%A3%85%E6%95%99%E7%A8%8B.jpg?token=AHMQUEPC4IFADOF5VG4QVN26Z64GG"
description: 从零开始安装 Linux Deploy
tags:
- Linux Deploy
- Android
---
# Linux Deploy 安装教程

小彧这里使用小米3移动版作示范

首先查询手机的安卓版本，当前的手机是4.4.4。根据安卓版本查询适用的busybox和linuxdeploy版本，分别是1.31.1和2.5.1。其中busybox组件负责linux指令的扩充，linuxdeploy负责建立容器运行linux。

安装步骤如下：

- 获取手机root权限
  
- 安装busybox-1.31.1
  
- 安装linuxdeploy-2.5.1
  
  1. 点击左上角 "三" —— "设置"，分别勾选"锁定WIFI"和"CPU唤醒"
    
  2. 点击右下角 "三"
    
    1. 发行版 GUN/Linux : Debian
      
    2. 架构 : AMRv7选择amrhf,AMRv8选择amr64
      
    3. 版本 : Debian 11
      
    4. 安装类型 : 镜像文件
      
    5. 用户名/用户密码 : "自行设置"
      
    6. 特权用户 : "请勿修改"
      
    7. 本地化 : zh_CN.UTF-8
      
    8. 初始化 : 启用
      
    9. 挂载 : 启用
      
    10. 挂载点列表 : `/mnt/shell/emulated/0:/mnt/ext0sd0`
      
    11. SSH : 启用
      
  3. 点击右上角图标 —— "安装"，等待安装完成
    
  4. 点击左下角“启动”
