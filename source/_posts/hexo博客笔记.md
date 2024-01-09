---
title: hexo博客笔记
toc: true
categories:
- 技术
tags:
- hexo
- 教程
---

# hexo
## 安装
```javascript
npm install -g hexo-cli
```
## hexo目录结构
```
.
├── _config.yml
├── package.json
├── scaffolds
├── source
|   ├── _drafts
|   └── _posts
└── themes
```
### _config.yml 
是网站的配置文件，设置网站的标题，描述，主题，插件，语言等信息
  
### package.json 
是应用程序的信息文件，设置应用程序的名称，版本，依赖，脚本等信息

### scaffolds 
是模板文件夹，定义不同类型的文章的模板，例如文章，页面，草稿等

### source 
是存放用户资源的文件夹，放置文章，图片，数据等
#### _drafts 
是存放草稿的文件夹，写一些未完成的文章，它们不会被生成到网站上
#### _posts 
是存放文章的文件夹，写正式的文章，它们会被生成到网站上。

### themes 
是主题文件夹，这里选择或者自定义你的网站的外观和功能。


## hexo命令
* hexo clean
* hexo generate
* hexo server