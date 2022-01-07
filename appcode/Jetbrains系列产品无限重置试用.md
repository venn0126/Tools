# Jetbrains系列产品无限重置试用


## 安装环境

本机环境

* Mac OS 11.6（Apple M1）

App版本

* AppCode 2021.1.3

插件适用范围

* `Jetbrains`系列产品`IDEA`,`AppCode`,`CLion`,`DataGrip`,`GoLand`,`PhpStorm`,`PyCharm`,`Rider`,`RubyMine`,`WebStorm`等都有30天的eval(试用期).

### 准备环境

[下载AppCode 2021.1.3](https://www.jetbrains.com/objc/download/)

[插件下载](https://github.com/venn0126/Tools/tree/main/appcode)

### 插件安装

#### 手动

* 首先打开AppCode,点击试用30天
* 安装插件
  *  直接把插件拖入到工具中
  * 在`AppCode-Preferences-Plugins`中安装
* 设置自动重置时间
  * `Help-Eval Reset`选中`Auto reset before per restart`，这个选项的意思是：自勾选后每次重启/退出IDE时会自动重置试用信息，你无需做额外的事情

#### 自动

* 增加插件仓库

![](https://github.com/venn0126/iOS-Study/blob/master/Resource/AppCode0.png?raw=true)

* 添加仓库地址`https://plugins.zhile.io`

![](https://github.com/venn0126/iOS-Study/blob/master/Resource/AppCode1.png?raw=true)

* 搜索`IDE Eval Reset`插件并安装

![](https://github.com/venn0126/iOS-Study/blob/master/Resource/AppCode2.png?raw=true)



### 如何使用

手动唤出插件的主题界面

* 如果`IDE`没有打开项目，在`Welcome`界面点击`IDE`菜单，`Get Help -> Eval Reset`
* 如果`IDE`打开了项目，点击`IDE`菜单，`Help -> Eval Reset`

![](https://github.com/venn0126/iOS-Study/blob/master/Resource/AppCode3.png?raw=true)

唤出的插件主题包含了一些显示信息，有两个按钮和两个勾选项

* 按钮`Reload`用来刷新界面上的显示信息
* 按钮`Reset`点击会询问是否重置试用信息并重启`IDE`，选择`YES`则执行重置操作并重启`IDE`生效，选择`NO`，什么也不会做
* 勾选项`Auto reset before per restart`如果勾选了，则自勾选后每次重启`IDE`时会自动重置试用信息
* 勾选项`Logout when reset`，如果勾选了，则自勾选后每次退出`IDE`时会自动重置试用信息

![](https://github.com/venn0126/iOS-Study/blob/master/Resource/AppCode4.png?raw=true)


## 查看到期时间
点击`AppCode -> About AppCode`

![](https://github.com/venn0126/iOS-Study/blob/master/Resource/AppCode5.png?raw=true)

查看到期时间

![](https://github.com/venn0126/iOS-Study/blob/master/Resource/AppCode6.png?raw=true)



## 后续

如有任何问题，请联系`weiniu@sohu-inc.com`
