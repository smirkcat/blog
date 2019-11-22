---
title: "第一篇博客"
date: 2019-11-22T11:12:45+08:00
draft: true
tags: ["hugo","hugo-theme-easybook"]
categories: ["hugo"]
---

### 博客搭建教程

1. 网站框架主题

- 框架 [hugo](https://github.com/gohugoio/hugo)
- 主题 [easybook](https://themes.gohugo.io/hugo-theme-easybook/)

2. 起步
到https://github.com/gohugoio/hugo/releases 下载指定二进制文件，解压到某个位置，添加目录进path变量，然后执行下面脚本

```shell
hugo new site smirkcat # 新建hugo项目
cd smirkcat
git clone https://github.com/Y4er/hugo-theme-easybook themes/easybook
cp themes/easybook/exampleSite/config.toml config.toml #修改
hugo new post/helloworld.md # 第一篇博客
hugo server -D # 测试
```
打开http://localhost:1313/ 观看效果

3. 发布github
