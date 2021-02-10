---
title: myspl
date: 2021-02-08 21:01:35
tags:
---

# 下载安装

下载地址: [官网](https://www.mysql.com/)

耐心等待.

- download 结束后就是安装了，next ，next 。。。。。。

- 安装结束后，发现在command 终端仍然不能使用mysql ，会提示the command not find ,这个原因是我们还需哟进行mysql 环境变量的配置；

- 首先要确认我们的mysql 已经在我们的电脑中了，路径是：/usr/local/mysql/bin/,我的是下面这样的：

- 接下来进行环境变量的设置咯：vim ~/.bash_profile 添加以下内容：

```
export PATH=$PATH:/usr/local/mysql/bin

alias mysql=/usr/local/mysql/bin/mysql

alias mysqladmin=/usr/local/mysql/bin/mysqladmin
```

- wq保存并退出

- 再source ~/.bash_profile 使上面的环境变量生效；

- 就可以在终端使用mysql 啦：command : mysql -u root -p 然后就输入在安装的时候设置的密码就可以了

- quit