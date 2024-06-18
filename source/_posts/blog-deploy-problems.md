---
title: hexo推送到github pages不执行部署的问题
date: 2024-06-12 21:36:36
tags:
index_img: /img/anime-street.png
banner_img: /img/anime-street.png
excerpt: 使用以分支发布的方法解决按照hexo官网一键部署后，推送到github仓库上后，但是没有执行action，导致博客访问不到的问题。
---
## 这是我使用了hexo官网的一键部署到github pages之后发现没有自动部署的问题

问题描述：一下大概就是能上传到自己的github仓库上，但是却不能访问到自己blog页面。

我的博客项目也是按照仓库名是github id加上github.io,https://kwings6.github.io/

[hexo官方的一键部署教程](https://hexo.io/zh-cn/docs/one-command-deployment)


然后我去查看了一下github pages的官方使用文档
[github pages官方的配置](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

我这里使用了第一种方法：以分支发布。

![github-pages-branch-deploy](../img/github-pages-branch-deploy.png)