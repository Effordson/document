[TOC]

参考文档：

[Obsidian之利用MaoXian获取网页信息](https://blog.csdn.net/haoyujie/article/details/127806743)



插件下载地址：

[install MaoXian Web Clipper](https://mika-cn.github.io/maoxian-web-clipper/install-by-extension-file-zh-CN.html)

# 安装

1、下载MaoXuan 浏览器插件

选这个：

maoxian-web-clipper-chromium-0.4.11.crx.zip

2、安装插件

安装前，要将chrome先置为开发者模式。

解压到插件目录如`C:\Users\58388\AppData\Local\Google\Chrome\User Data\Default\Extensions`，回到浏览器 扩展程序 =》加载已解压扩展程序

3、扩展插件=》详情=》允许访问文件网站和收集错误打开

# 配置

1、基础设置：

- 勾选：我设置好了 ‘允许插件访问本地文件路径’

2、存储设置：

- 保存格式：Markdown

3、Markdown

- Markdown模板：

```
---
date: {{createdAt}}
tags:
- maoxian
aliases: 
title: {{title}}
---

原文地址: {{url}} 

{{content}}

```

- 标题格式：**Atx-Style heads**
- 水平分割线： ---
- 子弹列表的行头符：- list item
- 代码块格式: Fenced
- 代码块分隔符: 3个反引号
- 斜体：星号
- 加粗：2个星号
- 链接格式：inlined



# 使用

1、左键单击扩展程序图标，选择区域

2、鼠标悬浮在右边提示条的“ON”上可以弹出操作菜单

3、Enter键保存页面