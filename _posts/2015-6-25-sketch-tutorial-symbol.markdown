---
layout:     post
title:      "[Sketch 3 教程] Symbol篇 V1.0"
subtitle:   " \"熟用此功能，妈妈再也不用担心我要熬夜了\""
header-img: "img/sketch3_icon.png"
---

Symbol 是 Sketch 3 中的新功能，它可以让你方便的在多个页面和画板中重复使用某组内容。熟练使用该功能，妈妈再也不用担心我要熬夜了。

## 为何要使用Symbol功能？

在设计UI的时候，大多数人都会遇到这样的情况：
在UI设计稿中，有一个控件几乎在每个界面里都出现。突然PM或甲方过来跟你说，这个控件颜色要换一换，然后你就很苦逼地一个一个地去改。
改好后，他们突然又过来说原来的方案好。这个时候，你也只能默默地从裤兜那踹出一把杀猪刀。。。。。

但是现在有了Symbol这个功能就不一样了。在当你需要修改一个共通的控件时，只需要修改其中一次即可。

![testing symbol]({{ http://www.questionhunt.com/sketch-tutorial-symbol/ }}/assets/sketch_symbol/testingSymbol.gif){: .aligncenter}


## 如何创建Symbol ？
选择一组编组（group）或者几个图层（layer），点击 layer > create symbol. 

![create symbol]({{ http://www.questionhunt.com/sketch-tutorial-symbol/ }}/assets/sketch_symbol/createSymbol.png){: .aligncenter}

点击 create symbol 后，左边的编组文件夹颜色会变成紫色，那么就意味着创建Symbol成功了。当你需要在其他artboad中插入这个Symbol时，只需要点击 Insert > Symbol 然后选择要插入的Symbol即可。

![organize symbol]({{ http://www.questionhunt.com/sketch-tutorial-symbol/ }}/assets/sketch_symbol/organizeSymbol.png){: .aligncenter}

## 如何删除Symbol ?
当你需要删除Symbol时，只需要点击 Insert > Symbol > Organize Symbols. 接着Sketch会弹出一个窗口，里面有你所创建的所有的Symbols，点击左下角的 － 号就可以删除这个Symbol。

![delete symbol]({{ http://www.questionhunt.com/sketch-tutorial-symbol/ }}/assets/sketch_symbol/deleteSymbol.png){: .aligncenter}

成功删除，紫色的Symbol文件夹就会变成普通的蓝色文件夹。点击close即可以关闭Symbol管理窗口。

## 如何取消Symbol ？
在使用Symbol的过程中，可能会遇到不想使用Symbol的情况。那么这个时候，你只需要右键点击紫色的编组 > Detach from Symbol。然后编组的文件夹颜色就会变成蓝色。

![detach symbol]({{ http://www.questionhunt.com/sketch-tutorial-symbol/ }}/assets/sketch_symbol/detachSymbol.png){: .aligncenter}

## Symbol 和 Style 有什么区别 ？
Symbol和Style两者功能可以说是一样的，但它们也有不同。简单说来Symbol是以编组（Group）为单位共享样式。而Style则是以图层（Layer）为单位共享样式。

举个例子。我们团队在设计App的时候，会同时使用Symbol和Style功能制作UI界面的上Bar。

![example]({{ http://www.questionhunt.com/sketch-tutorial-symbol/ }}/assets/sketch_symbol/example.png){: .aligncenter}

UI的上Bar包含两个编组：
1. Status Bar 手顶部的信号、电量显示的那条Bar。
2. Bar Title 上Bar显示的文字、颜色等。

我们在 Status Bar 采用Symbol功能，因为所有界面的 Status Bar 都是一样的。但是我们在 Bar Title 编组没有采用Symbol，因为你可以看到，每个上Bar显示的文字都不一样，有些是电话号码，有些则是地区。那么如果这个时候，使用Symbol的话，所有的上Bar文字都会变成相同的文字。

如果想解决这一问题，可以点击Symbol中的文字，再勾选右边的Exclude Text Value from Symbol。就可以将该文本排除出Symbol。

![exclude text]({{ http://www.questionhunt.com/sketch-tutorial-symbol/ }}/assets/sketch_symbol/excludeText.png){: .aligncenter}

但是这里只能排除文字，不能排除layer。回到刚刚的那个例子，上Bar除了含有文字、背景颜色外，还有一个回退按钮。但是这个按钮不是所有上Bar都有。

那么这个时候，我们就使用了Style功能，将上Bar背景设成 Shared Style。那么我们需要改上Bar的颜色的时候，只需改一次即可。





