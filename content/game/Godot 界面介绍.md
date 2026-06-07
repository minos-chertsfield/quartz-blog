---
title: Example Title
draft: false
tags:
  - example-tag
---

> [编辑器手册](https://docs.godotengine.org/zh-cn/4.x/tutorials/editor/index.html#doc-editor-introduction)
# 1、项目管理器

项目管理器页面可以管理已有项目、导入或创建新项目等等

![image.png](http://image-blog-001.test.upcdn.net/images/202605161752130.png)

另外，还有资产库选项卡，可以在这里浏览到各种开源社区开发的项目

![image.png](http://image-blog-001.test.upcdn.net/images/202605161754018.png)

点击这个页面的设置按钮，可以修改一些其他条目，像语言、界面主题等

![image.png](http://image-blog-001.test.upcdn.net/images/202605161756464.png)

>[使用项目管理器](https://docs.godotengine.org/zh-cn/4.x/tutorials/editor/project_manager.html#doc-project-manager)
# 2、Godot 编辑器

打开新建项目或者已有项目，都可以进入 Godot 编辑器界面

![image.png](http://image-blog-001.test.upcdn.net/images/202605161800676.png)

默认情况下，左侧为**主菜单**，中间为**工作区切换按钮**，右侧为**游戏测试按钮和电影制作模式切换按钮**

![image.png](http://image-blog-001.test.upcdn.net/images/202605161805765.png)

在中间的工作区切换按钮下方，是场景标签，点击 `+` 可以新建场景，右侧是专注模式

![image.png](http://image-blog-001.test.upcdn.net/images/202605161808742.png)

## 2.1、中间区域

在中间位置，场景选择器下方是**视口**，其顶部是工具栏，可以用于移动、缩放或锁定场景中的节点

![image.png](http://image-blog-001.test.upcdn.net/images/202605161811081.png)

工具栏会**根据上下文和所选节点改变**，这里是 **2D 工具栏**

![image.png](http://image-blog-001.test.upcdn.net/images/202605161814662.png)

然后，这个是 **3D 工具栏**

![image.png](http://image-blog-001.test.upcdn.net/images/202605161814796.png)

> [五个屏幕](https://docs.godotengine.org/zh-cn/4.x/getting_started/introduction/first_look_at_the_editor.html#doc-intro-to-the-editor-interface-five-screens)
> [3D 简介](https://docs.godotengine.org/zh-cn/4.x/tutorials/3d/introduction_to_3d.html#doc-introduction-to-3d)

视口的两边是**停靠面板**，窗口的底部则是**底部面板**

## 2.2、停靠面板

![image.png](http://image-blog-001.test.upcdn.net/images/202605161822443.png)

**文件系统**面板会列出项目中的文件，包括脚本、图片、音频采样等

![image.png](http://image-blog-001.test.upcdn.net/images/202605161830978.png)

**场景**面板中会列出活动场景中的**节点**

![image.png](http://image-blog-001.test.upcdn.net/images/202605161832719.png)

在**检查器**面板中可以查看所选节点的属性

>[检查器面板](https://docs.godotengine.org/zh-cn/4.x/tutorials/editor/inspector_dock.html#doc-editor-inspector-dock) 
>[面板的移动和大小调整](https://docs.godotengine.org/zh-cn/4.x/tutorials/editor/customizing_editor.html#doc-customizing-editor-moving-docks)

## 2.3、底部面板

视口底部的**底部面板**中包含了调试控制台、动画编辑器、混音器等，默认都是折叠状态

![image.png](http://image-blog-001.test.upcdn.net/images/202605161839838.png)

点击对应的 Tab 会纵向展开对应功能的面板，也可以使用快捷键
# 3、四个主屏幕

工作区有5个选项卡：2D、3D、Script、Game、AssetLib

**2D 屏幕**可以用于任何类型的游戏，除了 2D 游戏，2D 屏幕也会用于**界面的构造**

![image.png](http://image-blog-001.test.upcdn.net/images/202605161912530.png)

**3D 屏幕**可以操作网格、灯光、设计 3D 游戏的关卡

![image.png](http://image-blog-001.test.upcdn.net/images/202605161914246.png)

**Script 屏幕**是一个完整的代码编辑器，包含调试器、丰富的自动补全、以及内置的代码参考手册

![image.png](http://image-blog-001.test.upcdn.net/images/202605161916523.png)

**AssetLib 屏幕**是插件、脚本、资产的仓库，这些内容是开源的，可以直接在项目中使用

![image.png](http://image-blog-001.test.upcdn.net/images/202605161921797.png)

> [关于资产库](https://docs.godotengine.org/zh-cn/4.x/community/asset_library/what_is_assetlib.html#doc-what-is-assetlib)
# 4、内置类参考手册

Godot 自带内置的类参考手册
搜索类、方法、属性、常量、信号相关的信息，可以使用以下任意方法：
- 在编辑器中的任意位置按下 F1
- 点击 Script 主屏幕右上角的“搜索帮助”按钮
- 点击“帮助”菜单的“搜索帮助”
- 在脚本编辑器中 Ctrl + 点击类名、函数名、内置变量

![image.png](http://image-blog-001.test.upcdn.net/images/202605161929390.png)

![image.png](http://image-blog-001.test.upcdn.net/images/202605161932839.png)