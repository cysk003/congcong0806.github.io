---
layout:     post                    # 使用的布局（不需要改）
title:     Telegram 中文搜索解决方案              # 标题 
subtitle:  #副标题
date:       2019-11-04             # 时间
author:     Power-User                      # 作者
header-img:     #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - Telegram

---

##### 问题在哪
Telegram 群组和频道越来越多，消息也越来越多，但是搜索中文的消息却是一个很大的问题。<br>
主要原因：<br>
Telegram 的搜索是以"词"为基础单位的，是以`英文标点符号`或`空格`作为"词"的间隔。<br>
这是以英文为基础的搜索方式，这样的方式对于英文的搜索就很方便，比如"hello"，用"he"就搜索不到，必须用"hello"，这就符合英文的语境，当我想要找"he"消息时并不想看到有"hello"的消息。<br>
![](http://ww1.sinaimg.cn/large/9b84e6acly1g8lrgoijstj20750bngu4.jpg)

但是这种方式对于中文等语言来说就很不方便，中文是以字为单位的，按照上面的方式，比如消息内容"动态贴纸不能用这个bot导出"用"贴纸"或"导出"就不能搜索到此消息。

##### 如何解决
知道问题出在哪儿？那又如何解决呢？
解决方案：
* 发消息时以`英文标点符号`或`空格`作为间隔，比如消息"动态贴纸不能用这个bot导出"，可以用"动态 贴纸 不能 用这个 bot 导出"方法发出，这样就可以用"动态""贴纸""不能""导出"关键词搜索到此消息。
* 发消息时可以加'tag'，比如想发送消息"ABCDEFG"，可以发送"#tag ABCDEFG"，下次可以用"#tag"关键词搜索找到都有这个标签的消息。
* 已发的消息，以`标点符号`或`空格`作为间隔单位搜索，比如"好像国区是没有，点链接提示转到国区，关掉就好了，账号可以在不同地区购买"，可以用"好像国区是没有""点链接提示转到国区""关掉就好了""账号可以在不同地区购买"关键词搜索到此消息。
![](http://ww1.sinaimg.cn/large/9b84e6acly1g8lriq5f9mj20l30gab29.jpg)
![](http://ww1.sinaimg.cn/large/9b84e6acly1g8lriy0la0j20jj0h57wh.jpg)

##### Telegram 相关链接
* [Telegram 知识](https://congcong0806.github.io/2019/04/11/Telegram)
* [Telegram 官方客户端支持中文语言](https://congcong0806.github.io/2019/02/21/Telegram)
* [Telegram 各个系统客户端地址](https://congcong0806.github.io/2019/01/08/Telegram)
* [Telegram 群组、频道、机器人 - 汇总分享](https://congcong0806.github.io/2018/04/24/Telegram)
* [Telegram 中文搜索解决方案](https://congcong0806.github.io/2019/11/04/TelegramSearch)

> 转载请注明原文出处：[Telegram 中文搜索解决方案](https://bit.ly/36x6bTO)

- - - -

##### 优秀的正版软件
<https://congcong0806.github.io/2018/09/03/App>

##### Power-User
&copy;Power-User: Telegram, Surge, Clash
