---
title: test文章
date: 2026-09-21 20:03:28
categories:
  - 测试
cover: /img/posts/test/img-001.png
---

# 工程使用说明

1. 工程导入

- 打开Vitis，选择某个路径为工作空间并打开。

- 打开后，在上方工具栏选择“File”->“Import...”：

![](/img/posts/test/img-001.png)

- 然后在弹窗中选择“Vitis project exported zip file”，点击“Next”：

![](/img/posts/test/img-002.png)

- 然后点击“Browse”,选择工程压缩包，按照下图所示，勾选所有，然后点击“finish“，即可完成工程导入：

![](/img/posts/test/img-003.png)

1. 工程结构说明

- 工程包含了以太网测试代码（TCP、UDP测试）、emmc读写接口、usb接口例程，各部分在工程的位置如下：

![](/img/posts/test/img-004.png)

- UDP测试例程搭建了一个UDP服务器，本地端口为：20001，IP：192.168.1.10，其接收客户端发送的消息后，原样返回相同的信息给客户端。TCP测试和UDP测试基本相同，其端口号为：10001。

- IP和端口号可以在“network.h”文件进行修改。

![](/img/posts/test/img-005.png)
