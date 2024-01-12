---
title: "tr教程"

date: 2024-01-10T03:02:52+08:00

lastmod: 2024-01-11T03:02:52+08:00

description: 一个普普通通的教程（可能有错但问题不大）

tags:

- 泰拉瑞亚

categories:

- 技术

image: 
slug: tr



---

打不开局面的突破手，不敢奔向爱的懦夫

# 

## 第一步：下载工具

1.下载Tabby

![](A.png)

2.打开tabby并且点击

![](C.png)

3.输入服务器ip

4.进入后输入密码

![](B.png)

<br>

5.下载

```
yum install unzip
```

 

## 第二步: 运行服务端

1.我们先创建一个用来存放泰拉瑞亚服务器的文件夹

```
cd /
cd opt
mkdir tr
cd tr
```

2.下载服务端

```
wget https://terraria.org/api/download/pc-dedicated-server/terraria-server-1449.zip
```

3.解压

```text
unzip terraria-server-1449.zip
```

4.设置权限

```
cd /opt
sudo chmod -R 777 tr
cd tr
```

5.移动至Linux 服务端文件夹并运行对应版本

```
cd 1449/Linux/
./TerrariaServer.bin.x86_64
```

 

## 第三步：游戏配制

1.

```text
Terraria Server v1.4.4.9

n       New World
d <number>Delete World

Choose World: 
```

选择世界：输入数字选择已有世界、n为创建新世界、d+数字为删除对应编号的世界。目前无已有世界，我这里输入n选择创建新世界。

2.

```text
Terraria Server v1.4.4.9

1       Small
2       Medium
3       Large

Choose size: 
```

选择世界大小，输入数字1，2，3发别对应着小世界，中世界，大世界

3.

```text
Terraria Server v1.4.4.9

1       Normal
2       Expert

Choose difficulty: 
```

选择世界难度，1普通难度，2专家难度

4.

```text
Terraria Server v1.4.4.9

Enter world name: 
```

输入世界名称：我这里输入了666

5.

在输入完世界名称后便会开始创建世界，创建成功后会回到选择世界界面

```text
Terraria Server v1.4.4.9

1               666
2               easy
n       New World
d <number>Delete World

Choose World:
```

输入1，选择世界 666，接下下来会有4个选项，分别为：

```text
Max players (press enter for 16):
```

最大人数，默认16

```text
Server port (press enter for 7777):
```

服务端口，默认7777

```text
Automatically forward port? (y/n): 
```

自动转发端口？默认y

```text
Server password (press enter for none): 
```

服务器密码，默认无

(理论上直接按四个回车就可以)

全部填写完毕，等待服务器加载，出现以下界面则说明启动成功，使用ctrl+a+d可退出

```
Terria Server v1.4.4.9


Listening on port 7777
Type"heip"for a list of commands
:
```

## 特（保持服务器运行）

- 创建并进入名叫tr的screen

```text
screen -S tr
```

这行代码可以使服务器在电脑关闭时运行

# 感谢知乎[Nu11# ](https://www.zhihu.com/people/Elez)

# 本网站地址：

[https://blog.tbx.lockey.icu/](https://blog.tbx.lockey.icu/)

<br>
