kX驱动安装手册
=============
* 适用系统
  * Windows 7
  * Windows 8/8.1
  * Windows 10

* 驱动版本 kX 3552

* 点击页面右侧`Clone or download`并选择`Download ZIP`下载本项目所有文件

* 欢迎提交`issue`或`pull request`参与改进本手册

卸载已安装的 kX 驱动程序
----------------
1. 打开`控制面板`
1. 点击`卸载程序`
1. 右键`kx Audio Driver`
1. 卸载并重启

关闭杀毒软件
----------------
1. 右键已安装的`杀毒软件`，退出
1. 禁用`Windows Defender服务`

安装VC++ 2012可再发行组件包
----------------
1. 安装`Vcredist2012_x86.exe`

安装 kX 3552 驱动程序
----------------
1. 以管理员身份运行 `kX_3552_setup.exe`
1. 按提示安装驱动
1. 安装完成最后一步提示重启，点`取消`

64位系统额外步骤
----------------
1. 右键`kX_amd64_startup_fix.ini`，点击`安装`（修复注册表启动项）

Windows 10 额外步骤
----------------
1. 右键`C:\Program Files (x86)\kX Project\kxmixer.exe`，点击`属性`
1. 在`兼容性`选项卡内点击`以兼容模式运行这个程序`并选择`Windows 7`
1. 点击右下角的`确定`

重新启动
----------------

安装效果和插件
----------------
1. 重启后如果安装没问题会看见 kX 的启动界面
1. 将`effects&plugins`文件夹内的文件复制到`C:\Program Files (x86)\kX Project`下（不复制也没关系，但是要保证不要移动它们）
1. 右键任务栏 kX 图标并选择`kX 数字信号处理器`
1. 右键界面内任意位置并选择`注册插件`
1. 逐次注册`effects&plugins`内所有文件

* 安装 UFX 插件
1. 以管理员身份运行`ufx_setup.exe`
1. 按提示安装

载入效果
----------------
1. 右键任务栏 kX 图标并选择`kX 数字信号处理器`
1. 点击右侧`载入设置`
1. 选择要载入的文件

完成
----------------
* 如果一切顺利，那效果应该已经生效了
* 附赠本萌新制作的Effect`kXEffectByPeratX.kx`
  * 适用于`EMU10K1芯片`（包括SB0060，其他的应该也支持）
  * MX8调音台
  * EFX混响
  * BBE
  * EQ P5
  * 录音并没有任何效果，本萌新只是用来处理音乐
  
共享协议
----------------
This work is licensed under a [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).