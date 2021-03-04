LOFFER是个可以帮助你get off from LOFTER的软件。

这是一个可以发布在GitHub的Jekyll博客，你不需要编写代码或使用命令行即可获得一个部署在GitHub的博客。

此文档用于说明LOFFER的现有功能和更新情况，**查看为无代码基础者写的教程[请点这里](https://fromendworld.github.io/LOFFER/document/)**

## 其他的使用tips

### 2019-07-25 V0.4.0

1.对LaTeX渲染的支持，请见[这篇说明和示例](https://fromendworld.github.io/LOFFER/math-test/)。

2.置顶功能，只要在一个post的YAML Front Matter（就是文章头部的这段信息）中加入` pinned: true `，这篇文章就可以置顶了。

3.给LOFFER更换主题颜色的手法。LOFFER用了一个开源的颜色表[Open Color](https://yeun.github.io/open-color/),该色表提供的可选颜色有：red, pink, grape, violet, indigo, blue, cyan, teal, green, lime, yellow。

LOFFER的默认状态是teal，要更换主题颜色，只要打开文件` _sass/_variables.scss `，将文件中所有的teal全部替换成你想要的颜色。例如，查找teal，替换indigo，全部替换，commit，完成！


### 2019-07-20 V0.3.0

1.目录功能，在post的信息中心加入` toc: true `，这篇博文就会显示目录了。

目录基于[jekyll-toc by allejo](https://github.com/allejo/jekyll-toc)制作。


## 支持的功能

使用Markdown文档在_post文件夹中发布博文，现有功能包括显示作者、置顶博文、添加目录。

博文YAML举例：

    ---
    layout: post
    title: Markdown语法简介
    date: 2013-07-16
    Author: Shengbin 
    tags: [sample, markdown]
    comments: true
    toc: true
    ---

按照标签和日期查看博文归档。请查看/tags 和/archive 页面。


## 致谢

* [Jekyll](https://github.com/jekyll/jekyll) - 这是本站存在的根基
* [Kiko-now](<https://github.com/aweekj/kiko-now>) - fork这个主题，然后再其上进行修改汉化，才有了LOFFER
* [Font Awesome](<https://fontawesome.com/>) - 社交网络图标来自FontAwesome的免费开源内容
* [FromEndWorld](<https://github.com/FromEndWorld/loffer>) - 感谢FromEndWorld制作的LOFFER

## 帮助这个项目

介绍更多人来使用它，摆脱lofter自由飞翔！

欢迎Issues和Pull Requests。

给原作者项目点一个☆吧！（点击下图即可打开原作者github项目主页链接）

[![img](https://raw.githubusercontent.com/FromEndWorld/LOFFER/master/images/givemefive.png)](https://github.com/FromEndWorld/loffer)
