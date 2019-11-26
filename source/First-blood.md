---
title: 开篇啦
categories: blog
tags:
  - vim
  - git
  - nodejs
  - npm
  - hexo
  - next
  - markdown
  - balabala
abbrlink: 8af53e26
date: 2018-03-13 14:42:09
---
**终于，终于，终于写出来第一篇了！！**

<!-- more -->

五年前，我就打算要弄个博客，跟随我妈的步伐在新浪上开了一个篇，就没有然后了。后来在大三大四的时候，听说可以用`github+jekyll`搭建博客，讲真，可能没那么复杂，可是我就想拖啊拖，冠冕堂皇的给自己一个理由要学习标签上那堆东西（~~好吧，现在也没有学会~~）。到后来又听说了`hexo`，做了个收藏。毕设，毕业，工作，游戏。一晃三年过去了，想了想那点计划貌似连开篇都没过去。看了看新浪里的私密博文，时间定格在`2015-1-16`，考研后毕设前，那会儿的我，还能文绉绉的整点词，现在也不会了。毕业之前的，那篇私密的应该也讲得很多了，那就说说毕业后吧。

总的说呢，像 **_Eminem_** 的《Lose yourself》歌词一样：

> You only get one shot, do not miss your chance to blow.

是的，blow。三年我只记得四个手游，梦幻西游、皇室战争、阴阳师、王者荣耀。时间在上面悄悄地溜走，直到现在，若不是现在忙里偷闲，想来还要继续拖下去。
BUT，至少有个开头就是好的嘛（虽然不知道会不会有结尾）。好啦，正题正题。

-----

## 博客操作平台更新

1. vim升级，[vim官网](https://www.vim.org "vim")下载最新版本覆盖安装即可（注意保留安装目录下的\_vimrc）
2. git升级，[git官网](https://git-scm.com/ "git")下载最新版本覆盖安装即可，`git --verioin`查看版本
3. node.js升级，[node官网](https://nodejs.org/en/ "nodejs")更新覆盖安装，`node -v`查看版本
4. `npm install npm -g` #npm自更新，`npm -v`查看版本，升级完成后清缓存，`npm cache clean --force`
5. `npm update -g`更新npm安装的包（不知道包不包括npm本身）（npm淘宝镜像快一点）`npm ls --global -depth 0`（有报错，不建议经常更新稳定为主）
6. next主题更新，`git stash list`，解决冲突后`git add *`，`git stash`，`git pull`，`git stash pop`或`git stash drop`（注意保存主题配置文件\_config.yml）

## 博客常规操作

### 常用命令

``` bash
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #将.deploy目录部署到GitHub
```

### 常用复合命令

    hexo deploy -g
    hexo server -g

### 简写

    hexo n == hexo new
    hexo g == hexo generate
    hexo s == hexo server
    hexo d == hexo deploy

## Markdown基本语法

参考链接：[Markdown简明语法][1]，里面也有很多其他的链接，非常全面。

[1]: http://ibruce.info/2013/11/26/markdown/
