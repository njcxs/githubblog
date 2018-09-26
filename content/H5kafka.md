Title: kafka安装与使用
Date: 2018-06-04 13:20
Modified: 2018-06-04 13:20
Category: kafka
Tags: kafka
Slug: H5
Authors: nJcx
Summary: kafka相关

#### 安装

地址 

```bash

https://downloads.lightbend.com/scala/2.12.6/scala-2.12.6.tgz

http://mirrors.hust.edu.cn/apache/kafka/2.0.0/kafka_2.12-2.0.0.tgz

http://download.oracle.com/otn-pub/java/jdk/8u181-b13/96a7b8442fe848ef90c96a2fad6ed6d1/jdk-8u181-linux-x64.tar.gz

```

下载并且解压


```bash

cd /opt && download  ALL  && tar -zxvf  ALL

```

配置环境变量

```bash

echo -e "export JAVA_HOME=/opt/jdk1.8.0_181 \n\
export JRE_HOME=\${JAVA_HOME}/jre \n\
export CLASSPATH=.:\${JAVA_HOME}/lib:\${JRE_HOME}/lib \n\
export PATH=\${JAVA_HOME}/bin:\$PATH \n\

export SCALA_HOME=/opt/scala-2.12.6 \n\
export PATH=\$PATH:\$SCALA_HOME/bin \n\
" >> /etc/profile && source /etc/profile

```



