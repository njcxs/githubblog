Title: golang快速入门
Date: 2018-06-02 13:20
Modified: 2018-06-02 13:20
Category: golang
Tags: golang
Slug: H3
Authors: nJcx
Summary: golang学习后，转化成教程，方便大家阅读

##### 介绍

Go语言是谷歌与09年开源的一门编译型编程语言，其专门针对多处理器系统应用程序的编程进行了优化，支持并行进程，自动垃圾回收。Docker就是go语言所编写。


#### 安装
mac 电脑安装

```bash
brew install go
```
ubuntu

```bash
sudo apt-get install golang -y

```
CentOS 

```bash
yum install golang -y

```

#### 向世界打招呼


```go
package main 

import 'fmt'

func main() {
    fmt.Println('Hello world!')
}
```
####  数据结构


- 布尔型

```go
    var b bool = true
    c := false
```
- 数字类型
整型 int 和浮点型 float32、float64，Go 语言支持整型和浮点型数字，并且原生支持复数，其中位的运算采用补码。

- 字符串类型

```go
    var b string = 'demo'
    c :=  'godemo'
```

- 指针类型（Pointer）

- 数组类型

- 结构体类型(struct)

- Channel 类型

- 函数类型

- 切片类型

- 接口类型（interface）

- Map 类型

