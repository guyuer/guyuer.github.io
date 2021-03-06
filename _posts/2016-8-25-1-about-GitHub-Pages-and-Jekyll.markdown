---
layout: post
title:  "1.关于GitHub Pages和Jekyll"
date:   2016-08-25
categories: jekyll update
---

# 关于GitHub Pages和Jekyll

### Jekyll
* 主页：https://jekyllrb.com/
* 托管地址：https://github.com/jekyll/jekyll

#### —— 一个静态站点生成器。
GitHub Pages支持Jekyll生成普通的html内容。是一个流行的静态网站生成器。

GitHub Pages深度集成Jekyll，Jekyll是专为写博客和软件文档设计的一个静态网站生成器，但是还不止于此。使用Jekyll,可以创建重复使用的网页的头部和尾部，而不用复制它们到每一个页面中去。同时提供[一些高级的模板](http://jekyllrb.com/docs/templates/)和[Jekyll主题支持](http://jekyllrb.com/docs/themes/).

尽管GitHub Pages可以与任何静态网页生成器结合，但是使用Jekyll提供了许多内嵌的支持，而且GitHub为它提供了详细的官方文档。要获取更多详细信息关于怎样在GitHub Pages上使用其他的静态网站生成器，请看[使用除了Jekyll以外的静态网站生成器](https://help.github.com/articles/using-a-static-site-generator-other-than-jekyll/).

##### Jekyll的主要优势：
1.用Markdown代替HTML。[Markdown](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/)是阅读和写作都很简单；

2.你可以[添加Jekyll主题](https://help.github.com/articles/adding-a-jekyll-theme-to-your-github-pages-site)到你的网站，而不用复制CSS文件；

3.你可以使用通用模板，例如headers和footers模板，它们是通过文件共享的；

4.你能通过GitHub Pages简化站点的构建过程。

### Jekyll的构建过程
相对于用其他的静态站点生成器来说，Jekyll通过GitHub Pages简化站点的构建过程是其最大的优势，GitHub Pages用single push到你的网站发布分支来管理你的网站构建过程.下面是Jekyll管理网站的构建过程：

1.Push修改到你的发布分支；

2.GitHub Pages发布你的网站。

**Note:** The publishing branch you use depends on the type of GitHub Pages site you have.

1.For [User or Organization pages](https://help.github.com/articles/user-organization-and-project-pages/#user--organization-pages), use the master branch.

2.For [Project pages](https://help.github.com/articles/user-organization-and-project-pages/#project-pages), use the gh-pages or master branch. Alternatively, you can also publish your site from a /docs folder on the master branch. For more information, see "[Configuring a publishing source for GitHub Pages](https://help.github.com/articles/configuring-a-publishing-source-for-github-pages)."

### Jekyll网站案例
如果想使用GitHub Pages提供的内嵌支持，推荐使用Jekyll，包括[GitHub Pages gem]()管理依赖，特定的构建失败的信息和更多解决问题的帮助。

下面的列出了Jekyll网站的案例：

1.[Projects using GitHub Pages](https://github.com/showcases/github-pages-examples);

2.[Open source organizations using GitHub Pages](https://github.com/showcases/open-source-organizations).

### 更多阅读
要学习更多Jekyll知识，看[Jekyll官方文档](https://jekyllrb.com/).
