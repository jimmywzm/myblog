---
layout:     post
title:      "[Sketch 3 教程] Text 篇 V1.0"
subtitle:   " \"Text 基础教程\""
header-img: "img/sketch3_icon.png"
---
## 如何添加文本 ？
点击左上角insert > Text,然后点击你想要添加的位置，Artboard上就会出现Type something的字样。这个时候，就可以删除这行字，键入你想要的文字。最后，你只要鼠标点击文本以外的地方，就可以退出编辑模式。

![create text 01]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/createText01.gif){: .aligncenter}

另外一种方法则是使用快捷键T，点击T，鼠标会变成I符号，点击你想要添加的位置，Artboard上就会出现Type something的字样，之后就可以添加文本了。

![create text 02]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/createText02.gif){: .aligncenter}


## 如何编辑文本 ？
**双击** 你想编辑的文本，就会进入编辑模式。然后就可以编辑你想要编辑的文本了！

![edit text 01]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/editingText01.gif){: .aligncenter}


## 如何修改文本样式 ？
**单击** 你想要编辑的文本，sketch右边的检查器就会变成这样。

![edit text 02]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/editingText02.png){: .aligncenter}

然后你就可以修改你想要修改的内容了：

1. Typeface: 改变字体
2. Weight：Regular（常规体）Light（细体） Bold（粗体）
3. Options：添加下划线等。
4. Color：改变字体颜色。
5. Size：改变字体大小。
6. Alignment：改变排版样式。
7. Width：更改文本框宽度。（分自动模式与固定模式）
8. Spacing：间距。（字母间距、行间距、段间距）
9. Opacity：不透明度。
10. Blending：混合模式。


## 文本框宽度自动模式与固定模式有何区别 ？
自动模式下：文本框会自动扩展以容纳一切文本。

![width auto]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/widthAuto.gif){: .aligncenter}

固定模式下：则会在你输入文本时，保持原有宽度不变，而增加文本框的高度。

![width fix]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/widthFix.gif){: .aligncenter}


## 如何使用Text on Path功能 ？
Text on Path 功能可以让你的文本根据一定的路径排列。比如这样：

![text on path]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/textOnPathExample.png){: .aligncenter}

那要实现这个功能需要：
1. 将图形图层放在文本图层下面。（这一点很重要，放在上面是不行的。）
2. 点击屏幕顶端的Type > Text on Path。

![text menu path]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/textMenu_path.png){: .aligncenter}

3. 将文本拖动到图形那，Sketch会自动将Text置于Path上。

![text on path]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/textOnPath.gif){: .aligncenter}


## 如何将Text转换为矢量图形 ？
要将Text转换为矢量图形，只需要选中你需要转换的文本，然后点击屏幕顶端的Type > Convert Text to Outlines。（或者快捷键 Shift + Command + O）

![text menu outlines]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/textMenu_outlines.png){: .aligncenter}

Text中的每个字母都可以单独编辑了。需要注意的是，Sketch官方推荐在转换的时候，尽量之转换少量文本。如果一次转换大量的文本，Sketch需要比较长的处理时间。如果真的需要转换长文段，最好就分多次转换，一个长文段分成几个短文段。

![convert text to outlines 02]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/convertTextToOutlines.png){: .aligncenter}


## 为何要将Text转换为矢量图形 ？
如果你想要单独编辑文本中的字母，就一定要使用Convert Text to Outlines功能，但是其实Convert Text to Outlines在制作UI的时候会非常有用。原因如下：

1. 在制作UI的过程中，遇到要让某个按钮变大的情况，设计师通常采用鼠标拉伸的方式让按钮变大。如果按钮中有一个普通的文本。会这样：<br/>
![why use convert text to outlines 01]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/whyUseConvertTextToOutlines01.gif){: .aligncenter} <br/>
2. 如果是使用了Convert Text to Outlines呢？使用了此功能后，文本也会随着鼠标的拉伸而变化了。<br/>
![why use convert text to outlines 02]({{ http://www.questionhunt.com/sketch-tutorial-text/ }}/assets/sketch_text/whyUseConvertTextToOutlines02.gif){: .aligncenter}
