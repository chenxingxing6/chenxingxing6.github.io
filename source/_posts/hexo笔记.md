---
title: hexo笔记
date: 2017-10-24 15:15:29
tags: 学习日志
---
hexo常用命令笔记
----------
**1.写文章**

```
hexo new "文章名"
```

**2.编辑文章**

> 可以用[CSDN-markdown](http://write.blog.csdn.net/mdeditor)先在本地写，边写边看效果。最后将文章拷贝到文件中，并push到github。

**3.Push到github**

```
hexo clean #清除缓存 网页正常情况下可以忽略此条命令
hexo g #生成静态网页
hexo d #开始部署
hexo server #启动服务预览
```

**4.模版**

```
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口
hexo deploy #将.deploy目录部署到GitHub
```


