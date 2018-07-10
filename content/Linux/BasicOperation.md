---
title: "Basic Operation"
date: 2018-07-10T10:15:20+08:00
draft: false
---

- 先对原来的sources list进行备份：
输入命令：sudo cp /etc/apt/sources.list /etc/apt/sources.list.bk

- 把软件的更新源编辑进去，放在文末或者最前面都行：
输入命令：sudo gedit /etc/apt/sources.list

---
- 部分国内开源镜像站点列表：
- 清华大学（http://mirrors.tuna.tsinghua.edu.cn/）
- 中国科学技术大学(debian.ustc.edu.cn)
- 上海交通大学(ftp.stju.edu.cn)
- 大连理工大学(mirror.dlut.edu.cn)
- 北京交通大学(mirror.bjtu.edu.cn)
- 北京理工大学(mirror.bit.edu.cn)
- 东北大学(mirror.neu.edu.cn)
- 厦门大学(mirrors.xmu.edu.cn)
- 兰州大学(mirror.lzu.edu.cn)
- 西安电子科技大学(linux.xidian.edu.cn)
- 哈尔滨工业大学(run.hit.edu.cn)
- 天津大学(mirror.tju.edu.cn)
- 东软信息学院(mirrors.neusoft.edu.cn)
- 电子科技大学(mirrors.stuhome.net)
- 华中科技大学(http://mirror.hust.edu.cn/)
- 网易开源镜像站(mirrors.163.com)
- 搜狐(mirrors.sohu.com)
-   
- 找到Ubuntu，打开help即可

---

- 更新源信息：
输入命令：sudo apt-get update

- 更新软件：
输入命令：sudo apt-get upgrade xxx
