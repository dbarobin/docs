# 项目说明 #

本项目搜集了我工作中写过的文档。提供文档索引、文档摘要。

**声明**
所有文档未公开。

# 更新日志 #

2015-01-15

> 文档版本为「1.0」,文档名为「文档索引」,备注为「所有文档的索引,包括文档名、编号、文档摘要」,By Robin。

2015-01-22

> 文档版本为「1.0.1」,文档名为「文档索引」,备注为「添加 032-Zabbix 部署文档」,By Robin。

# 文档索引 #

* 001-GitLab文档
* 002-Jetty CAS 单点登录
* 003-Linux 修复 Bash 漏洞
* 004-Ubuntu 解压文件乱码解决方案
* 005-Ubuntu 命令行查询字典
* 006-Ubuntu 制作部分本地源
* 007-Docker 搭建文档
* 008-硬件 MAC 信息
* 009-SVN 配置文档
* 010-Redmine 和 Git 结合
* 011-RedMine 配置文档
* 012-虚拟环境配置说明文档
* 013-自动生成侧边栏目录
* 014-生产环境修复 Bash 漏洞
* 015-Memcached 部署文档
* 016-阿里云服务器间项目移植
* 017-Redis 部署文档
* 018-Windows下使用 Git 教程
* 019-Git 使用说明书
* 020-TortoiseGit 使用说明书
* 021-MySQL 导入 cmms 数据
* 022-MySQL 配置文档
* 023-Mac 安装配置 MySQL
* 024-MySQL 集群建议
* 025-VPS 利用 ShadowSocks 搭建 VPN
* 026-Python 自动化部署
* 027-MongoDB 部署文档
* 028-Hackintosh 安装文档
* 029-Maven 部署文档
* 030-MediaWiki 部署文档
* 031-PHP 项目 Rewrite
* 032-Zabbix 部署文档
* 033-Mac 支持 NTFS 读写

# 文档摘要 #

## 001-GitLab文档 ##

> GitLab 是一款开源的源代码管理系统,核心是 git,提供类似 GitHub 的友好界面供用 户使用。 本文档运行平台为 Ubuntu，已完全测试通过。本文档基于 GitLab 搭建, 数据库采用 MySQL, Web 服务器采用 Nginx, 实现 HTTPS 加密访问, 并使用 Gitolite 进 行权限管理。本文档记录了搭建 GitLab 的完整过程。

## 002-Jetty CAS单点登录 ##

> Apache + Jetty 实现 CAS 单点登录。

## 003-Linux 修复 Bash 漏洞 ##

> 修复 Bash 漏洞，该文档已经部署在 GitBook 中。

## 004-Ubuntu 解压文件乱码解决方案 ##

> Ubuntu 解压文件出现乱码，尝试解压各种格式的压缩文件，总结出没有乱码的方法。

## 005-Ubuntu 命令行查询字典 ##

> Ubuntu 命令行查询字典，可以使用 dictd 和 stardict 两种方式。

## 006-Ubuntu 制作部分本地源 ##

> Ubuntu 制作本地源，加快访问速度。

## 007-Docker 搭建文档 ##

> 使用 Docker 总结的文档。

## 008-硬件 MAC 信息 ##

> MAC 地址与 IP 地址绑定。

## 009-SVN 配置文档 ##

> SVN 服务器部署。

## 010-Redmine 和 Git 结合 ##

> 整合 Redmine、Gitolite 和 Git。

## 011-RedMine 配置文档 ##

> Redmine 部署在 s1，数据库使用 MySQL，并且和 Gitolite 结合使用。Redmine 和 Gitolite 的 repo 同步，然后 s1 再同步到 s2。我们通过 s2 访问以及更新项目，通过浏览器输入 http://xxx.xxx.xxx.xxx:xxxx/ (公网访问)或者 http://xxx.xxx.xxx.xxx:xxxx/ (内网访问)访问 Redmine 界面，Web 版的 Redmine 只提供浏览。

## 012-虚拟环境配置说明文档 ##

> 配置虚拟环境。

## 013-自动生成侧边栏目录 ##

> Markdown 自动生成侧边栏目录。通过执行 tocmd 命令，把 *.md 转成 html，并带有 toc 功能。

## 014-生产环境修复 Bash 漏洞 ##

> 生产环境更新 Bash 漏洞。脚本自动执行。

## 015-Memcached 部署文档 ##

> 部署 Memcached。

## 016-阿里云服务器间项目移植 ##

> 阿里云服务器之间项目迁移，数据库同步。

## 017-Redis 部署文档 ##

> Redis部署，环境为Debian 7.6。

## 018-Windows下使用 Git 教程 ##

> Windows 下使用 Git 教程，供开发者使用。目前文档版本为 2.0。

## 019-Git 使用说明书 ##

> Git 使用说明书，供 Windows 环境下用户使用。

## 020-TortoiseGit 使用说明书 ##

> TortoiseGit 使用说明书，供 Windows 环境下用户使用。

## 021-MySQL 导入 cmms 数据 ##

> MySQL 导入 cmms 数据，该文档供测试人员使用。提供导入脚本。

## 022-MySQL 配置文档 ##

> 二进制方式部署 MySQL，并且附有源码编译方法。

## 023-Mac 安装配置 MySQL ##

> 在 Mac 下使用 brew 安装 MySQL，使用源码编译 MySQL 5.1，并且提供运行多个 MySQL 的方法。

## 024-MySQL 集群建议 ##

> MySQL 集群建议。主主复制被动模式+ Slave + MMM。

## 025-VPS 利用 ShadowSocks 搭建 VPN ##

> 在一台位于美国的 VPS 服务器上，使用 Shadow Socks 搭建 VPN，供科学上网使用。

## 026-Python 自动化部署 ##

> Python 自动化部署，本机只需执行脚本，远程即可自动部署。脚本采用 Python 编写，远程调用使用 Fabric 实现。该项目已经托管在 GitHub，地址：https://github.com/dbarobin/python-auto-deploy

## 027-MongoDB 部署文档 ##

> 部署 MongoDB文档。

## 028-Hackintosh 安装文档 ##

> 在 PC 上安装 Hackintosh。使用镜像为原版 OS X Mavericks 10.9.3 和 10.9.5。

## 029-Maven 部署文档 ##

> 部署 Maven，并且通过 Nexus 实现 Web 访问。

## 030-MediaWiki 部署文档 ##

> 部署 MediaWiki，使用 MySQL 5.5。

## 031-PHP 项目 Rewrite ##

> 解决 PHP 项目点击页面出现 404 问题。

## 032-Zabbix 部署文档 ##

> 在一台监控服务器上搭建 Zabbix Server，监控其他服务器。

## 033-Mac 支持 NTFS 读写 ##

> 使用第三方软件支持 Mac 读写 NTFS 格式的移动硬盘。

# 作者信息 #

温国兵

* Robin Wen
* Gmail：dbarobinwen@gmail.com
* Blog：http://dbarobin.com
* GitHub：https://github.com/dbarobin
