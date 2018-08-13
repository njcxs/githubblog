Title: 抓包和规则编写-NIDS
Date: 2018-05-29 13:20
Modified: 2018-05-29 13:20
Category: 安全
Tags: nids
Slug: H1
Authors: nJcx
Summary: 抓包和nids规则编写

#### 两种抓包方式

1，来自客户端的抓包方式

- 工具：wireshark

- 介绍：wireshark是一个网络包分析软件。Wireshark使用WinPCAP作为接口，直接与网卡进行数据报文交换。

- 目的：分析客户端的发出的请求以及服务器响应

	![ml1](../images/WX20180813-161129.png)

2，来自服务端的抓包方式

- 工具: bro

- 介绍: Bro是一款被动的开源流量分析器。它主要用于对链路上所有深层次的可疑行为流量进行一个安全监控。更通俗点说就是，Bro支持在安全域之外进行大范围的流量分析，分析包括性能评估和错误定位。

- 协议  支持多种应用层协议 DNS FTP HTTP IRC SMTP SSH SSL 等等

- 目的: 接受和分析来自链路的流量

	![ml1](../images/WX20180813-161105.png)

#### 目的

确定指定字段包含或者等于指定内容。

#### NIDS规则的编写

- PATH(HTTP)

- UA(HTTP)


