# Caplos - CapsLock#

A tool to squeeze the power of your CapsLock key.

一个充分利用你的大小写键的工具, 可以最小化打字/写代码时的按键距离.

## 功能

* 大小写状态指示

软件会在任务栏显示为一个绿叶图标, 当你的键盘为大写状态时, 图标是绿色, 当小写时, 图标为白色.

* 可扩展的按键替换

本程序实现了真正的按键替换，可以完全等效为目标按键。比如你输入法选字的时候也可以用，代码提示选代码也可以用。还可以让 大小写键和 CTRL 等按键集成，比如一般状态下 Ctrl+← 是向左跳一个单词，使用本工具可以让 Ctrl+大小写+H 同样实现向左跳一个单词。

* 没有其它凌乱臃肿不必要的功能

体积仅 50kb 满足需求.

## 使用方法

按下 \[大小写键\] 的同时按下其它按键, 可执行替换后的按键的功能.

举例:

使用组合键 `[大小写]+H/J/K/L` 移动光标

使用组合键 `[大小写]+'` 进行退格删除

如果你是单手打字爱好者, 这个程序能让你更加轻松地打字.

## 键位表 (可自定义)

![键位表](https://pluvet-1251765364.cos.ap-chengdu.myqcloud.com/CDN/2019/07/27/1564216524.png)

(如果没加载出来, 到[这里](https://www.pluvet.com/archives/calos.html)也可以看)

## 设置项

### 如何自定义键位？

首次运行后，会生成 `Caplos.cfg` 文件，编辑即可。

### 如何自定义图标是否显示？

编辑 `Caplos.exe.config`，找到 `<add key="showIcon" value="true"/>` 配置项，`true`  表示显示，`false` 表示不显示。

## 下载地址:

1. 可以直接下载二进制文件: https://wwx.lanzoui.com/idVu9rj3h8j (2021-07-17更新)
2. 此版本支持 Ctrl+Space 切换中英文。仅供测试：https://wwx.lanzoui.com/iby7Xrj3tgj
3. 也可以自己编译

## 开源地址：

https://github.com/pluveto/caplos/

