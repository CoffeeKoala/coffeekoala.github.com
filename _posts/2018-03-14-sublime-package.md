---
layout:       post
title:        "sublime 插件推荐集合"
subtitle:     "工欲善其事"
date:         2018-03-14 19:00:00
author:       "CoffeeKoala"
header-mask:  0.2
catalog:      true
multilingual: true
tags:
    - 技术
    - sublime
---


> 行色秋将晚,交情老更亲。
> 动手之前先念两句诗 = =
> 
> 久别重逢非昨日，千言万语不忍谈
> 
> 日出东海落西山，愁也一天，喜也一天。
> 
> 遇事不钻牛角尖，人也舒坦，心也舒坦。


收集一些能够显著提高工作效率的插件。

package官网：https://packagecontrol.io/

### 为了更高的效率

 - package Control
     + 自行百度之

 - SFTP
    自动link本地folder到远程server
    可以通过设置实现自动保存上传至server，外加自动更新。需要配置;
    相比于直接brower server，在本地建立文件夹+link to server 会安全一些;
    没有对比过sublime 自带Git，个人感觉submit最好用svn ci 自己搞一下;

 - FileHeader
    新建文件自动加文件头，可根据文件后缀自动改格式，亲测优于snippet，    保存时自动更新编辑时间。 样例如下：

>  -*- coding: utf-8 -*-
>
>  @Author: coffeeKoala
>
>  @Date:   2018-03-12 11:48:57
>
>  @Email:  coffeeKoala@hotmail.com
>
>  @Last Modified by:   CoffeeKoala
>
>  @Last Modified time: 2018-03-12 11:57:48
>

- Graphviz
    需后台安装相应引擎，调用core类型要自己手动配置，效率低于Gvedit


 - wakaTime
    准确记录每个folder下花费了多久时间。
    按工作目录和语言皆有，需要注册；

- plainTasks
    一个插件堪比一个软件，非常好用的todolist;

- sideBarEnhancements
    copyFileName + copy Path + Reveal 用的比较多;


- sideBarFolders
    多工程目录上会提高效率;

- FileDiff
    在没有svn的情况下比较好用


### 为了更好看一点点

#### Display

- theme

- Opacity
    半透明界面，边代码边摸鱼不是梦 ^ ^
- Transparency


#### 格式化代码


- pretty Json

- SQL beautifier


### 强迫症患者福音
- TrailingSpace，去掉多余空格，强迫症患者福音。怀疑这个功能已经被集成了。

-- 自带: setting trim_trailing_white_space_on_save

-- 插件: trailing_spaces_trim_on_save

- Alighment，快捷键可自行设置，不对齐不舒服斯基

- CTRL+SHIFT+M：选中括号内内容，可用于检测括号匹配；

- Ctrl + P + # + @ 多文件跳转 查找变量定义+ 查找函数定义，个人感觉和gotoDefinition 差不多，习惯键盘操作则前者会快一点;





