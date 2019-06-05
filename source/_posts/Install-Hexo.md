---
title: Install Hexo
date: 2019-05-24 13:41:39
tags:
---

# Install Hexo/Nodejs/Nmp-------------------

## Install Nodejs
### method one
``` bash
$ sudo apt-get install python-software-properties
$ curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
$ sudo apt-get install nodejs
$ node -v
v8.5.0
$ npm -v
v5.3.0
```
### method two
``` bash
$ wget https://nodejs.org/dist/v10.9.0/node-v10.9.0-linux-x64.tar.xz  
$ tar xf  node-v10.9.0-linux-x64.tar.xz     
$ cd node-v10.9.0-linux-x64/                  
$ ./bin/node -v             

$ln -s /usr/software/nodejs/bin/npm   /usr/local/bin/ 
$ln -s /usr/software/nodejs/bin/node   /usr/local/bin/                  
```

## Install Nmp
``` bash
$ sudo npm install -g nrm
$ npm -v
```

## Install Hexo
``` bash
$ cd d:/hexo
$ npm install hexo-cli -g
$ hexo init blog
$ cd blog
$ npm install
$ hexo g 
$ hexo s 
```


