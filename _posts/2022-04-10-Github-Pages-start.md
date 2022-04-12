---
title: 使用 Github Pages + Jekyll 搭建个人博客
description: 记录自己使用 Github Pages + Jekyll 搭建个人博客的全过程
date: 2022-04-10 21:39:30
categories:
 - 原创
tags:
 - GitHub Pages
---

### 创建博客仓库

步骤参见：[创建 GitHub Pages 站点 - GitHub Docs](https://docs.github.com/cn/pages/getting-started-with-github-pages/creating-a-github-pages-site)

仓库创建完成后，便可通过仓库名访问博客内容了，不过由于我们没有添加主题和内容，所以看到的是一个空页面。

### 选择博客主题

GitHub pages 为我们提供了若干个 Jekyll 主题，使用较为简单，配置步骤参见：[使用主题选择器将主题添加到 GitHub Pages 站点 - GitHub Docs](https://docs.github.com/cn/pages/getting-started-with-github-pages/adding-a-theme-to-your-github-pages-site-with-the-theme-chooser)

当然，也可以使用自定义的 Jeklly 主题，[Jekyll Themes](http://jekyllthemes.org/) 提供了很多可选的主题，通过如下步骤便进行配置：

1. 将创建好的博客仓库 clone 到本地
2. 将下载的主题文件解压到clone的目录下
3. 修改 _config.yml 文件内容

再次访问博客地址，不出意外的话，便能看到主题已经生效了。

### 发布博客

在 _posts 目录下，创建一个md文件，命名格式为 “年-月-日-标题.md” ，下面是一些例子：

```
2021-04-01-我的第一篇博文.md
2021-04-01-my-first-post.md
```

文件头信息内容类似如下：

```
---
title: 使用 Github Pages + Jekyll 搭建个人博客
description: 记录自己使用 Github Pages + Jekyll 搭建个人博客的全过程
date: 2013-12-24 23:31:30
categories:
 - 原创
tags:
 - GitHub Pages
 - 
---
```

此时，上传了这篇博文到博客仓库，再次访问博客地址，就能看到这篇博文已经添加到博客中了。
