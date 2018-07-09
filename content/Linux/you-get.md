---
title: "you-get"
date: 2018-07-09T20:22:30+08:00
draft: false
---

在Linux下非常好用的视频下载工具you-get，其中github的地址：https://github.com/soimort/you-get

---
- 安装:
- sudo apt-get update
- sudo apt-get install python3 python3-pip rtmpdump git vlc
- sudo apt-get install ffmpeg
- git clone git://github.com/soimort/you-get.git
- cd you-get
- sudo python3 setup.py install

---
- 使用：
- 1、在线播放：you-get -p vlc "视频地址"
- 2、下载：
- 视频详细信息：you-get -i "视频地址"
- 查看视频的真实地址：you-get -u "视频地址"
- 下载到一个指定的文件夹：you-get -o /home/lw/movice/ "视频地址"
- 指定清晰度（从视频详细信息中获取）: you-get --format=hd3 "视频地址"

---
-原文：https://www.qingsword.com/qing/1348.html