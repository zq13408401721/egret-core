白鹭引擎 5.0.0 发布日志
===============================


最近更新时间：2017年6月5日


欢迎您使用白鹭引擎

## 概述

白鹭引擎包含了白鹭时代研发的遵循HTML5标准的游戏引擎。他包括 2D / 3D 渲染核心、GUI体系、音频管理、资源管理等游戏引擎的常用模块。

通过使用白鹭引擎，开发者可以尽可能的不用关注浏览器的底层实现，解决HTML5游戏性能问题及碎片化问题，灵活地满足开发者开发2D或3D游戏的需求。

本次更新是白鹭引擎 5 的一个小升级，主要修复一些 BUG

## 更新内容

* EUI
    * 修复 4.1 版本引入的为一个图片设置 source 属性后，宽高长度为0 的BUG

* 声音
    * 修复在 QQ 空间 Android App 上，音乐无法正常播放的 BUG

## 已知问题

* 开发者如果使用 WebAssembly 渲染，目前会在类的静态变量声明处创建对象时报错
* WebAssembly 渲染目前暂不支持 EUI 模块与 DragonBones 模块
