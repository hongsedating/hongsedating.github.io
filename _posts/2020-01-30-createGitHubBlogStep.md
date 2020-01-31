---
layout: default
title: github创建博客步骤
---

此文章暂时只记录创建博客过程中的一些信息，待整理。
[Github Pages + jekyll 全面介绍极简搭建个人网站和博客](https://blog.csdn.net/tom_221x/article/details/84630283){:target="_blank"}
[博客项目目录结构](https://jekyllrb.com/docs/structure/){:target="_blank"}

**jekyll的目录结构**
我们只需要关注几个核心的目录结构如下（可以自己创建）：

* _layouts （存放页面模板，md或html文件的内容会填充模板）
* _sass（存放样式表）
* _includes （可以复用在其它页面被include的html页面）
* _posts（博客文章页面）
* assets（原生的资源文件）
  - js
  - css
  - image
* _config.yml （全局配置文件）
* index.html, index.md, README.md （首页index.html优先级最高，如果没有index，默认启用README.md文件）
* 自定义文件和目录