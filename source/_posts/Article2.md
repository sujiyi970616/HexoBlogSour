title: Article2(to remind me of the process)
tags:
  - Hexo
  - English
  - build
categories:
  - 我的过程
author: MGSU
date: 2020-02-27 21:07:00
---
## The process of my build

### First step 
Set up the environment of Git 、Nodejs and Hexo

### Second 


<!--more-->
Use the Hexo to build blog

with the code 
```
$ hexo init <folder>
$ cd <folder>
$ npm install
```


then, use the code to test on local host
```bash h
$ hexo g
$ hexo server
```

with the ctrl+c to stop the Server

### The Third step
To create a repository on my own Github and connect it

before connectting, I must install deployer command


```
$ npm install hexo-deployer-git --save
```

open the _ _config.yml_ file on the root
modify the value of deploy and add repo branch value on it

and last build connect with

```
$ hexo clean
$ hexo g
$ hexo d
```

### Visualize

use "hexo new "title" to create a new article

and put your own things on it.

then display it.


![upload successful](/images/pasted-2.png)
<!--more-->