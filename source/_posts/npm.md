title: 淘宝npm镜像使用方法
date: 2016-01-08 10:41:15
tags: hexo
---

镜像使用方法（三种办法任意一种都能解决问题，建议使用第三种，将配置写死，下次用的时候配置还在）:  
- 通过config命令
npm config set registry https://registry.npm.taobao.org 
npm info underscore （如果上面配置正确这个命令会有字符串response）  
- 命令行指定
npm --registry https://registry.npm.taobao.org info underscore   
- 编辑 ~/.npmrc 加入下面内容
registry = https://registry.npm.taobao.org

