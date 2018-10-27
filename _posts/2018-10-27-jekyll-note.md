---
layout: post
title: 'Jekyll note'
date: 2018-10-27
author: Jekyll
cover: 'http://on2171g4d.bkt.clouddn.com/jekyll-banner.png'
tags: jekyll
---

> 个人博客记录

### 第一次使用jekyll

jekyll是一个ruby语言编写的静态页面生成器.
可以把MarkDown格式的文件,生成html.
不仅仅这么简单,它可以通过模板,标签可以写出页面布局.并生成html.
设计出一个好的布局,添加适宜的功能组件,一次性生成静态的html框架.
剩下的就是添加我们的内容.
将内容和结构分开.以静态的方式发布网站.非常适合个人blog.

那么要想深入的学习jekyll是费是费力的活.尤其是非前端开发者.那如何快速利用jekyll建立自己的blog呢?
答案就是**themes**.

先找到自己中意的主题.然后git下来.
修改其中文件.最后push上去就可以了...

### 具体操作步骤

以linux为例.我使用的是arch.

> sudo pacman -S ruby
> gem install jekyll bundler
> jekyll new myblog
> cd myblog
> bundler install
> bundler exec jekyll serve

这是建立一个默认主题的站点,并通过它自带的功能进行预览.





