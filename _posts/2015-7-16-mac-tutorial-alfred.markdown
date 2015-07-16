---
layout:     post
title:      "[Mac 教程] Alfred 篇 V1.0"
header-img: "img/alfred.jpg"
---

## Alfred 是什么 ？
如果要给所有的Mac应用排一个最佳应用榜的话，Alfred 绝对是排在前五，甚至有可能问鼎冠军。其实Alfred是一个效率启动器，当然你其实不必在意效率起动器是什么，只需要在意它能干什么。

## Alfred 能干什么 ？
首先Alfred有付费及免费版本，付费版本多了一些高级功能，高级功能会在文章后面稍作介绍。

免费版本，主要是有两大功能：
1. 搜索
2. 系统操作

**搜索又分为本地搜索、字典搜索以及网络搜索，三个部分。**
1. 本地搜索功能 （包括本地文件、应用等）
	键入你想找的东西，Alfred就可以快速地帮你找到它。比如需要快速找到计算器，只需要键入“计算器”即可，然后Alfred会帮你启动计算器。<br/>
  ![alfred example 01]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredExapmle01.gif){: .aligncenter}<br/>
2. 字典搜索
	键入你想查询的单词，Alfred会自动链接字典。<br/>
  ![alfred example 02]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredExapmle02.gif){: .aligncenter}<br/>
3. 网络搜索
	键入你想要搜索的东西，然后按下回车键即可。Alfred甚至可以设置自定义搜索，比如我想要搜索Bilibili上的东西，我也可以在Alfred上完成。<br/>
  ![alfred example 03]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredExapmle03.gif){: .aligncenter}<br/>

**系统操作分为计算器、系统操作。**
1. 计算器功能非常简单。输入你想要算的东西，Alfred会自动帮你算好。<br/>
  ![alfred example 04]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredExapmle04.gif){: .aligncenter}<br/>
2. 键入像关机（shut down）等系统命令，可以关闭计算机。<br/>
  ![alfred example 05]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredExapmle05.gif){: .aligncenter}<br/>

## Alfred 如何使用 ？
从[官网]处下载Alfred，并安装。
  ![alfred website 01]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredWebsite01.png){: .aligncenter}
然后打开Alfred。接着屏幕顶部会有个帽子的icon。点击这个icon，再点击Preferences。
  ![alfred setting 01]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredSetting01.png){: .aligncenter}
接着屏幕会弹出这样的界面：
  ![alfred setting 02]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredSetting02.png){: .aligncenter}
上面有个Alfred Hotkey的项目，默认为Option + 空格。这就意味着要使用Alfred，只需要按下Option + 空格即可。

## Alfred 如何设置 ？
在Preferences中，有几个比较常用的修改。
1. Alfred Hotkey。（可以修改呼出Alfred的热键）
2. Appearance （主题设置，在右边可以选择你想要的主题。）<br/>
  ![alfred apperance 01]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredAppearance01.png){: .aligncenter}
3. Features 内的 Web Search。<br/>
  ![alfred features 01]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredFeatures01.png){: .aligncenter}
	要想添加你需要Web Search，其实很简单。以Bilibili为例，首先点击右下角“Add Custom Search”。<br/>
  ![alfred features 02]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredFeatures02.png){: .aligncenter}
	然后打开浏览器，点开Bilibili网站，在官方搜索框内键入一些内容。然后点击搜索，接着将该搜索页面的网址复制下来。<br/>
  ![alfred features 03]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredFeatures03.gif){: .aligncenter}<br/>
	比如我键入“文明”二字：[http://www.bilibili.com/search?keyword=文明&orderby=&formsubmit=&type=comprehensive&seid=7067591634709909690]将该网址粘贴到Search URL。
	接着将这个网址中“文明”二字及他们后面的东西删除，换成{query}。那么最后网址就是[http://www.bilibili.com/search?keyword=\{query}]。最后在Title处填上：Search Bilibili for '{query}’。Keyword可以设成你喜欢的快捷键。如果想个性化一点，再从网上下一个B站的icon，拖到下图的框中的位置。
  ![alfred features 04]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredFeatures04.png){: .aligncenter}
	一切搞好，点下Test，如果一切顺利，就会这样最后点击Save。
  ![alfred features 05]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredFeatures05.gif){: .aligncenter}<br/>
	如果需要添加其他的网站，都只需要将键入的内容及内容后面的东西删除换成{query}即可。
	这里给大家一些常用的网站：
	淘宝：http://s.taobao.com/search?q=\{query}
	维基百科中文：http://zh.wikipedia.org/wiki/'{query}'
	百度：http://www.baidu.com/s?wd='{query}'

## Alfred 的高级功能是什么 ？
要想开启高级功能，则需要购买官网的Powerpack（alfredWebsite02）。一个售价17英镑，大概170元人民币。<br/>
![alfred website 02]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredWebsite02.png){: .aligncenter}
高级功能就是Workflow，简单说来就是插件。安装不同的插件，会有不同的功能。比如豆瓣插件：<br/>
![Alfred Workflow]({{ http://www.questionhunt.com/mac-totorial-alfred/ }}/assets/mac_alfred/alfredWorkflow.gif){: .aligncenter}<br/>（alfredWorkflow）

## 从哪里可以下载到 Alfred 的 Workflow ？
hzlzh大神制作了一个Workflow的网站：[http://www.alfredworkflow.com]可以在这个网站那下载到很多好用的Workflow。
也可以从官方论坛下载：[http://www.alfredforum.com/forum/3-share-your-workflows/]
