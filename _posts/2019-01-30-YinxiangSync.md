---
layout:     post                    # 使用的布局（不需要改）
title:      印象笔记 Evernote Windows 客户端"无法连接到服务器"和"同步失败", 如何解决？             # 标题 
subtitle:    #副标题
date:       2019-01-30              # 时间
author:     聪聪                      # 作者
header-img:     #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - 印象笔记
    - Evernote

---
##### 印象笔记 Evernote Windows 客户端"无法连接到服务器"和"同步失败", 如何解决？

###### 第一步
用 Internet Explorer (以下简称:IE) 浏览器试试能否打开这个地址？**必须 IE 浏览器**<br>
印象笔记网页版:<https://app.yinxiang.com/Home.action>

如果找不到 IE 在哪儿, 文件路径:`
C:\Program Files\Internet Explorer\iexplore.exe`

###### 第二步
如果 IE 不能打开此地址, 依次打开:`IE右上角设置→Internet选项→"连接"选项卡→点击打开"局域网设置"`
![](http://ww1.sinaimg.cn/large/9b84e6acgy1fznji1hs0bj20c90c0wyx.jpg)

看一下"使用自动配置脚本"和"代理服务器", 是否勾选上, 并且填写有代理服务器地址

如果填写有代理服务地址, 核实一下此代理是否可用

**如果代理不可用或代理软件已关闭, 取消勾选"使用自动配置脚本"和"代理服务器", 然后再试下 IE 能否打开上面的印象笔记网页版**

###### 第三步
`IE 右上角设置→Internet选项→“高级”选项卡→SSL那部分:`<br>
勾选“使用TLS 1.0/1.1/1.2”和“使用SSL 2.0”选项, 并取消勾选“使用SSL 3.0”选项, 没有就不管
![](http://ww1.sinaimg.cn/large/9b84e6acgy1fznjpkp4xwj20d70iz7wh.jpg)

###### 第四步
如果按照第二步和第三步中的操作后, "IE"依然无法打开印象笔记网页版<br>
操作:`Internet选项→"高级"选项卡→重置 Internet Explorer 设置→重启 IE 和电脑→再试下 IE  能否打开网页`<br>
或者用其他软件修复一下"IE"<br>
不管用什么办法, 首先得让 IE 能打开上面的印象笔记网页版, 客户端才能使用<br>
印象笔记 Evernote 客户端遵从系统网络设置, IE的设置就是系统的网络设置

###### 第五步
按照第四步的操作后, "IE"依然无法打开印象笔记网页版, 可以用其他浏览器或同一网络下的其他设备试试能否打开网页版, 如果其他浏览器也不能打开网页就检查下你的网络了

###### 第六步
如果"IE"能打开印象笔记客户端, 可印象笔记客户端依然同步失败(同步按钮有叹号), 就得看具体的活动日志<br>
`印象笔记 Windows 客户端→菜单栏→帮助→活动日志→另存为, 文件私聊发我看看`

**我的联系方式:**
* 印象笔记工作群聊:<171606257@qq.com>
* QQ 邮箱:<171606257@qq.com>
* QQ 群:[310980586](https://jq.qq.com/?_wv=1027&k=549SGYY),[579754294](https://jq.qq.com/?_wv=1027&k=5JdOiol)
* Telegram 私聊:<https://t.me/congcongx_bot>
* Telegram 社群:<https://t.me/YinxiangBiji>

**或者联系印象笔记官方客服和技术支持帮你解决问题:**
* 官方微博:<https://weibo.com/yinxiangbiji>
* 官方微信:yxbj100
* 官方技术支持:<https://app.yinxiang.com/SupportLogin.action>

> 转载请注明原文出处:[印象笔记 Evernote Windows 客户端"无法连接到服务器"和"同步失败", 如何解决？](https://congcong0806.github.io/2019/01/30/YinxiangSync)

- - - -

##### 优秀的正版软件
<https://congcong0806.github.io/2018/09/03/App>

##### 聪聪
&copy;聪聪:Power-User:Telegram/Surge/Clash

* Telegram 私聊:<https://t.me/congcongx_bot>
* Telegram 社群:<https://t.me/YinxiangBiji>
* Telegram 频道:<https://t.me/YinxiangBiji_News>

![聪聪](https://i.v2ex.co/3wc207g5.png)