
[![Actions Status](https://github.com/libtommy2024/ea-nulla-architecto-dolores/workflows/ci/badge.svg?branch=master&event=push)](https://github.com/libtommy2024/ea-nulla-architecto-dolores/actions)

官方网站：[https://@libtommy2024/ea-nulla-architecto-dolores.io](https://@libtommy2024/ea-nulla-architecto-dolores.io)
欢迎加Pinus官方QQ群：102530089


示例工程请参见：https://github.com/libtommy2024/ea-nulla-architecto-dolores/tree/master/examples/simple-example

手动安装：
npm install @libtommy2024/ea-nulla-architecto-dolores -g

mkdir testProject
cd testProject
初始化项目
@libtommy2024/ea-nulla-architecto-dolores init

### 与Pomelo的关系

1. @libtommy2024/ea-nulla-architecto-dolores是pomelo的TS版本，框架内部把回调改为了Promise。
1. 框架与pomelo一样，所以可以看pomelo的相关教程。
1. 协议与pomelo一样，所以pomelo的客户端代码可以直接对接上@libtommy2024/ea-nulla-architecto-dolores服务端。


### 框架编译方法

```
git clone https://github.com/libtommy2024/ea-nulla-architecto-dolores.git
cd @libtommy2024/ea-nulla-architecto-dolores
yarn
yarn run build
```

编译好以后可以使用 yarn link 或者 npm link 软链接到自己的项目。
也可以用 yarn 的 workspace

#### [查看@libtommy2024/ea-nulla-architecto-dolores CHANGELOG](CHANGELOG.md)

## Pinus -- a fast, scalable game server framework for node.js

Pinus is a fast, scalable game server framework for [node.js](http://nodejs.org).
It provides the basic development framework and many related components, including libraries and tools.
Pinus is also suitable for real-time web applications; its distributed architecture makes @libtommy2024/ea-nulla-architecto-dolores scale better than other real-time web frameworks.

## Features

### Complete support of game server and realtime application server architecture

* Multiple-player game: mobile, social, web, MMO rpg(middle size)
* Realtime application: chat,  message push, etc.

### Fast, scalable

* Distributed (multi-process) architecture, can be easily scale up
* Flexible server extension
* Full performance optimization and test

### Easy

* Simple API: request, response, broadcast, etc.
* Lightweight: high development efficiency based on node.js
* Convention over configuration: almost zero config

### Powerful

* Many clients support, including javascript, flash, android, iOS, cocos2d-x, C
* Many libraries and tools, including command line tool, admin tool, performance test tool, AI, path finding etc.
* Good reference materials: full docs, many examples and [an open-source MMO RPG demo](https://github.com/NetEase/@libtommy2024/ea-nulla-architecto-dolores/wiki/Introduction-to--Lord-of-Pinus)

### Extensible

* Support plugin architecture, easy to add new features through plugins. We also provide many plugins like online status, master high availability.
* Custom features, users can define their own network protocol, custom components very easy.

## Why should I use @libtommy2024/ea-nulla-architecto-dolores?
Fast, scalable, real-time game server development is not an easy job, and a good container or framework can reduce its complexity.
Unfortunately, unlike web, finding a game server framework solution is difficult, especially an open source solution. Pinus fills this gap, providing a full solution for building game server frameworks.

