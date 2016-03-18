# iOS-Foundation
iOS架构（1）项目结构
网上的目录结构有很多种，以下自己项目常用的目录：
![](https://github.com/Erickson0806/iOS-Foundation/blob/master/iOS_dir.png?raw=true)

###3Libs
> 无法通过cocoaPods加入一些三方库

###AppDelegate
>AppDelegate及其扩展category

###Extension
>常用的Extension及业务需要的Extension

###General
>一些可以复用的公共组件

###Helpers
>一些帮助ViewController瘦身的工具

###Macro
>所有的宏定义文件
		|-	AppMacro.swift
		|- NotificationMacro.swift
		|- Libs.swift
  		|- UtilsMacro.swift

###Models
>与数据有关的models类

###Resources
>App用到的一些资源文件，如plist等

###ViewControllers
>控制器，更具业务在具体细分

###Views
>视图，更具业务具体细分


