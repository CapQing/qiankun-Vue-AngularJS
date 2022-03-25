# qiankun-Vue-AngularJS
利用微前端实现库乾坤(qiankun)，配置：Vue主应用+AngularJS微应用 / AngularJS主应用+Vue微应用 / Vue主应用+Vue微应用

## 项目背景
由于种种原因，接手技术栈不熟悉或过于老旧的前端项目，维护和增加功能变得艰难，此时可以通过微前端解决，笔者就遇到了AngularJS项目嵌入Vue2项目的情况。

## 乾坤介绍
https://qiankun.umijs.org/zh/guide
qiankun 是一个基于 single-spa 的微前端实现库，旨在帮助大家能更简单、无痛的构建一个生产可用微前端架构系统。  

### 什么是微前端
```
Techniques, strategies and recipes for building a modern web app with multiple teams that can ship features independently. -- Micro Frontends

微前端是一种多个团队通过独立发布功能的方式来共同构建现代化 web 应用的技术手段及方法策略。
```
微前端架构具备以下几个核心价值：

+ 技术栈无关  
  主框架不限制接入应用的技术栈，微应用具备完全自主权

+ 独立开发、独立部署  
  微应用仓库独立，前后端可独立开发，部署完成后主框架自动完成同步更新

+ 增量升级  
  在面对各种复杂场景时，我们通常很难对一个已经存在的系统做全量的技术栈升级或重构，而微前端是一种非常好的实施渐进式重构的手段和策略

+ 独立运行时  
  每个微应用之间状态隔离，运行时状态不共享


## TODO
1. Vue主应用+AngularJS微应用
2. AngularJS主应用+Vue微应用
3. Vue主应用+Vue微应用
