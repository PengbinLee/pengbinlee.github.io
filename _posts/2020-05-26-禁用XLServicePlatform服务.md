---
title: 禁用XLServicePlatform服务
description: 
categories:
 - Other
tags: 迅雷
---
安装迅雷极速版后，会注册产生XLServicePlatform服务，该服务无法通过修改启动类型来禁用，在重启迅雷或重启系统后，该服务的启动类型会重新被重新设置为自动启动，并自动开启服务。

可通过以下方法禁用XLServicePlatform服务

1. 关闭迅雷，在任务管理器中，手动停止XLServicePlatform服务，并设置其启动类型为禁用

2. 进入`C:\Program Files (x86)\Common Files\Thunder Network\ServicePlatform`目录下，删除`XLSP.dll`文件，然后新建同名空文件替换（当前目录可能无法创建文件，在其他目录创建好复制到此目录即可）