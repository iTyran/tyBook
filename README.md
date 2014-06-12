# 目录


## A tour of Cocos2d-x 3.0

> 以一个小游戏为例来介绍cocos2d-x 3.0的用法，包括Game loop, Scene graph, 碰撞检测，播放声音，显示分数等内容。
这个章节主要是带领读者进入cocos2d-x世界，同时也可以让老的读者复习一下cocos2d-x 3.0的新功能。

## What's new in cocos2d-x 3.0？
> 这一章主要介绍cocos2d-x 3.0引入了哪些新特性。在介绍这些特性的时候，不用拘泥于具体细节。旨在激发新老读者对cocos2d-x 3.0的信心和兴趣。

1. 引擎简介
2. 开发环境的搭建
3. 创建Hello World项目，并编译到不同平台设备
	- Windows
	- Mac
	- iOS
	- Android
4. 分析cocos2d-x引擎的文件结构
5. 游戏Demo介绍 ----------(总述一款游戏的大致逻辑层次，方便下文对基础的讲解)
6. 3.0与2.0比较
    - 命名方式
    - 物理引擎
    - 渲染
7. 约定
   - 命名空间与类名称
   - 构造函数和初始化
   - 选择器

## Scene Graph(Node,Layer, Scene, Sprite, Particle, Label), Coordinate system

> 这一章主要讲cocos2d-x的基本概念。着重突出一些"pattern"，比如addChild, positioin/scale/rotate/color/skew/操作，另外，需要引入一个小游戏。
并以此游戏为基本，讲一下如何扩展自己的类。比如如何继承一个自己的Sprite。（这个游戏可以选跑酷游戏）

1. 导演（Director）
- 场景（Scene）
	- 场景转换（Transitions）
- 层（Layer）
- 精灵
	- 精灵类（Sprite）
	- 精灵集合(SpriteBatchNode)
	- 精灵帧(SpriteFrame)
	- 精灵帧缓存(SpriteFrameCache)
- CCNode
- TexturePacker编辑器
- 菜单（Menu）
- 文本（Label & LabelTTF & LabelBMFont）	
- 开始一个跑酷游戏

## Actions, animations, event dispatcher, 
> 除了介绍这些内容外，突出Sprite atlas的概念。同样另入新的元素到跑酷游戏当中

1. Action介绍
	- 瞬时动作(ActionInstant)
	- 延时动作(ActionInterval)
		- 动画动作(Animate)
		- 移动动作(MoveBy & MoveTo)
		- 贝塞尔动作(BezierBy & BezierTo)
		- 其他
	- 复合动作
	- 变速动作
	- 自定义动作
	- 更新动作之定时器
	- scheduleUpdate
	- schedule

- 帧动画
- 骨骼动画
    - 使用情形
    - Cocos2d-x中的骨骼动画
    - 骨骼动画的使用
    - 骨骼动画制作工具Spine,Cocostudio
    
- 用户交互（査鑫）
	1. 触摸操作的处理机制
		- 单点触摸
		- 多点触摸
	- Android按键处理

- 让人物动起来


## 数据结构和内存管理
> 非常重要。要保存用户数据，引入数据结构的概念

1. 内存管理介绍
2. 常用内存管理方式
3. Cocos2d-x内存管理方式
4. 内存分配与释放原则
5. Cocos2d-x对象的生命周期


## basic physics
> 以chipmunk为基本引入物理到跑酷游戏

1. box2d & chipmuck 介绍
- 新物理接口介绍与使用
- 重力加速器
- PhysicEditor

## ui system
> 介绍ui系统及用法

  1. CocosBuilder
  - CocoStudio


## 文件处理，声音，粒子效果

1. 为什么要使用缓存
- Cocos2d-x 3.0中的缓存系统
- 数据存储方式
	- CCUserDefault
	- 格式化存储
	- 本地文件存储
	- XML与Json
	- SQlite
	
1. 使用音效引擎　　
	- 支持格式
	- 预加载背景音乐 & 音效　　
	- 播放背景音乐 & 音效

2. 粒子系统介绍
	- 粒子系统的使用
	- 编辑器:粒子编辑器的使用



## 简单的关卡编辑（使用plist或者json）
1. 常用格式和工具
- Tiled 介绍 & 使用
- 瓦片地图制作
- 加载瓦片地图
- TiledMap
- 自定义关卡格式


## 网络，数据库，多线程（简单介绍cocos2d-x有哪些辅助模块）
1. 网络传输框架
- cocos2d-x 3.0 网络库
- 阻塞与非阻塞
- 多人多站同步
	- 时间同步
	- 鱼群同步

## Extending cocos2d-x,如何编写自己的ui控件，如何编写自己的action，如何制作跨平台的组件。

## OpenGL ES和new renderer

## 游戏性能、内存泄露检测及优化。

## 跨平台移植（主要是android和wp8）

## 总结，wrap it all



