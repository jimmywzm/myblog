---
layout:     post
title:      "[Sketch 3 教程] Export篇 V1.0"
subtitle:   " \"Sketch 3 的杀手锏之一\""
header-img: "img/sketch3_icon.png"
---

在 Sketch 3 中，可以导出三种文件：
1. Artboard
2. 图层
2. 切片

## 如何导出 Artboard ？
选中需要导出的Artboard，再点击 Sketch 3 右下角的 Make Exoprtable。然后可以选择需要输出的尺寸，点击 + 号既可以添加更多的尺寸。在Sketch中，可以选择任意倍数输出，只需要在size内输入你想要输出的倍数即可。然后再点击下方的Export即可。建议将一倍尺寸文件的Suffix命名为@1x。<br/>
![export artboard]({{ http://www.questionhunt.com/sketch-tutorial-export/ }}/assets/sketch_export/exportArtboard.gif){: .aligncenter}

## Suffix 是什么 ？
在输出文件的时候，可以看到一个suffix选项，默认会自动添加。比如两倍则是@2x，输出的文件名中就会出现@2x。这个的作用就是方便设计师管理输出的文件。

## 如何导出图层 ？
如果你需要导出Artboard中的一个图层，你也可以按照同样的流程导出PNG文件。（ Sketch 3 默认输出PNG格式 ）<br/>
![export layers]({{ http://www.questionhunt.com/sketch-tutorial-export/ }}/assets/sketch_export/exportLayer.gif){: .aligncenter}

## 如何导出切片 ？
有的时候，设计师可能需要在一个文件内同时输出两个或多个图层。比如，现在这种情况：<br/>
![export slices example]({{ http://www.questionhunt.com/sketch-tutorial-export/ }}/assets/sketch_export/exportSlicesExample.png){: .aligncenter}<br/>

确定与删除键是两个图层，如果使用上面的方法去输出文件的化，Sketch 3 输出两个文件 —— 一个确定，一个删除。如果你只希望输出一个文件，那么就需要使用切片功能。<br/><br/>
![export slices]({{ http://www.questionhunt.com/sketch-tutorial-export/ }}/assets/sketch_export/exportSlices.gif){: .aligncenter}<br/>

## Sketch 3 右上角的 Export 是用来干嘛的 ？
点击右上角的 Export，Sketch 3 会出现一个窗口，里面会有所有可以输出的图层、Artboard、切片等。你只要勾选你想要输出的东西，然后点击Export即可。但你可能会发现，这个窗口没有你想要的图层。那是因为在这个窗口内，只会显示那些你已经 Make Exportable 的图层。当你需要统一输出文件的时候，只需要将你需要export的图层 make exportable即可。还需要注意的一点是，从这里输出，只会输出你在Exportable那设置的输出倍数。<br/>
![export example]({{ http://www.questionhunt.com/sketch-tutorial-export/ }}/assets/sketch_export/exportFunctionExample.gif){: .aligncenter}
