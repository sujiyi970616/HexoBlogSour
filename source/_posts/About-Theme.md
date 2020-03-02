title: About Theme
author: MGSU
tags:
  - build
  - 主题布置
categories:
  - 我的过程
date: 2020-02-28 13:42:00
---
## This Time is about theme 'Next'

### For the First Moment 

clone the package from Github [theme-next](https://github.com/theme-next/hexo-theme-next.git)

then Edit the _ _config.yml_ 

![upload successful](/images/pasted-5.png)
to change the theme

### With the Second


<!--more-->

Clean the previous frame then run on localhost
``` 
	hexo clean
	hexo g
   hexo s
```


### Visualize Own Layout


There is a file in the directory of theme named _ _config.yml_ which can set by my own favorite

This is the Scheme of the webpage use `'#'` to hide that is not your prefer
![upload successful](/images/pasted-7.png)

un `'#'` the tags in the menu to show these

![upload successful](/images/pasted-6.png)

### 添加分类页面

在git命令里面输入
```
hexo new page categories
```
在新建的categories 的页面中修改添加属性

![upload successful](/images/pasted-16.png)

至于文章添加分类直接可在本地`localhost`后加/admin 进入即时编辑页面


### Setting Profile Photo(avatar_头像)
这里是关于头像的设置和网站图标的设置

![upload successful](/images/pasted-8.png)

关于头像应该放于主题文件夹下的`source/images/` 再修改地址即可

在主题配置文件中修改favicon的值 将要放置的图标文件放在 `/source/images/` 下


![upload successful](/images/pasted-9.png)

### 页面底部信息设置


![upload successful](/images/pasted-10.png)

### 在页面右上角设置github链接

![upload successful](/images/pasted-11.png)