# DataMeter-12Fix



中文说明：
插件：DataMeter-12Fix
作者：Minuit
修改：Crazy HipHop
介绍：兼容IOS7-12上以系统和64位支持
 
-通知中心显示wifi和数据流量信息
-状态显示数据传转速率
-按天,周,月显示数据使用情况
-可通过设置选项自定义显示


插件已经patcher并且修复在IOS12上RootlessJB中完美工作

PC用ssh或者手机用Filza讲插件导入相对应的目录中

在没有remount的情况下，只能保证悬浮窗+状态栏正常工作，小部件是不工作的，只需要导入Library路径的文件即可
在确定remount的情况下，可以使其小部件工作，但是似乎不完美，手里没有其他设备见谅，全部导入路径即可

全部导入完毕之后，记住一定要inject

命令如下

inject /var/LIB/MobileSubstrate/DynamicLibraries/*.dylib

inject /var/LIB/PreferenceBundles/*.bundle 

injecy /System/WeeAppPlugins/*.bundle

快捷方便
然后执行注销
killall SpringBoard
即可如果觉得麻烦，可以直接重启后激活即可，然后去设置中进行插件配置。
有问题推特反馈，谢谢～！




English description


Tweaks: DataMeter - 12fix
Author: Minuit
Modify: Crazy HipHop
Description
Compatible with iOS 7, 8, 9, 10 ，11 and 12（RootlessJB)

Language: Chinese & English

- Notification Center widget display wifi and data traffic information
- Status Bar Display Network Data Rate 
- By day, week, month display data usage
- Configure Notifications from Settings


The plug-in has patcher and fixes work perfectly in RootlessJB on IOS12

PC SSH or mobile phone with Filza speak plug-in import corresponding directory
In the absence of remount, you can only guarantee that the hover window + status bar will work, and the widget will not work. You can simply import the files in the Library path
In the case of remount, you can make the widget work, but it doesn't seem to be perfect, and I'm sorry I don't have another device in my hand, so I'll just import the entire path


Inject some medicineswhen everything is injected

The command is

inject /var/LIB/MobileSubstrate/DynamicLibraries/*.dylib

inject /var/LIB/PreferenceBundles/*.bundle

inject /System/WeeAppPlugins/*.bundle


Quick and convenient
And then execute the logout
Killall SpringBoard

If you feel trouble, you can directly restart the activation, and then go to the Settings of the plug-in configuration.
If you have any questions, please send them to twitter. Thank you！



