---
layout: post
title: 用jekyll写文章
---
尝试学习使用jekyll来总结自己将要学习的知识。

###1. 创建带有默认目录结构的博客在默认的github项目下

```
jekyll new .
```

###2. 可以在_posts目录下创建自己的第一篇文章，我选择使用markdown，所以需要注意的一点是，文章头必须包含如下的yaml头格式：

> layout: post | default | page
> 
> title: title
> 
> xxx: xxx

###3. 任何在_config.yml文件内的改动都不会被jekyll server监控到的，所以如果有改动，需要重启jekyll server
