# Mac OS安装Sublime Merge

## 1. 下载文件

+ 下载`Sublime_Merge_Dev_Build_2057__HCiSO_.dmg`文件

## 2. 安装过程
+ 点击`Sublime_Merge_Dev_Build_2057__HCiSO_.dmg`安装包，然后按提示进行磁盘安装
+ 安装完成之后，打开`Sublime Merge`--`Help`---`verify license`
+ 把安装包内的文本内的内容，全部复制到2中的位置，点击验证即可，如果失效请联系楼主

## 3.禁止自动检查更新
+ 打开工具栏中的`Preference`-`Edit Settings`
![](https://media.discordapp.net/attachments/569722032137437191/874229291653689354/unknown.png?width=811&height=533)

+ 输入以下代码

```
// Settings in here override those in "Default/Preferences.sublime-settings",
// and are overridden in turn by syntax-specific settings.
{

	"update_check": false
}

```

![](https://media.discordapp.net/attachments/569722032137437191/874229712073949214/unknown.png?width=962&height=533)