---
layout: post
title: 磁盘结构
description: 计算机上，数据写在磁盘上，那么，磁盘是什么结构？磁盘读写速度有没有瓶颈？
category: computer system
---

##磁盘

硬盘大小：台式机3.5寸，笔记本尺寸2.5寸。

下图为硬盘的物理结构：

![true-disk](/images/computer-system-disk/true-disk.jpg)

上图可以直观看出，硬盘包含如下几个基本结构：

* 盘片*（存储数据）*
* 磁头*（向盘片，读取/写入数据）*
* 主轴马达
* 机械手臂

给一个正在读取磁盘内容的近景图：

![disk-reading](/images/computer-system-disk/disk-reading.JPG)

###磁盘内部结构

（扇区、磁柱、磁轨）
（多区记录技术）

下面将对磁盘涉及的专业术语进行简要介绍，先来一张磁盘结构的简图：

![cylinder_head_sector](/images/computer-system-disk/cylinder_head_sector.svg)

###磁盘的接口

SATA？IDE？SCSI？

###选磁盘注意事项


###查看磁盘详情

查看步骤；

###测试磁盘读写速度


[NingG]:    http://ningg.github.com  "NingG"