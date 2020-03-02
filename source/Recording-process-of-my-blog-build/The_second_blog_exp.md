---
title: Recording process of my blog build
date: no time
---
## The process of build

### First step 
Set up the environment of Git Nodejs Hexo

### Second 
Use the Hexo to build blog

with the code 
'''bash 
$ hexo init <folder>
$ cd <folder>
$ npm install
'''bash

then, use the code to test on local host
'''bash 
$ hexo g
$ hexo server
'''bash

### The Third step
To create a repository on my own Github and connect it

before connectting, I must install deployer command

'''bash
$ npm install hexo-deployer-git --save
'''bash

open the _ _config.yml_ file on the root
modify the value of deploy and add repo branch value on it

and last build connect with

'''bash
$ hexo clean
$ hexo g
$ hexo d
'''bash

### Visualize

use "hexo new "title" to create a new article

and put your own things on it.

then display it.

