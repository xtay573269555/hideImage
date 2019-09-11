图片隐写，将要隐藏的文字写入图片中，理论上最大可支持几十M文本。
原理比较简单，可见代码注释。

经过处理的图片和原图在肉眼上几乎没有区别，并且在体积上不会造成明显膨胀。
（处理后的体积可能略微膨胀，甚至会变小）

运行方式
```
java -jar  -Dfile.encoding=UTF-8  target/hideImage-1.0-SNAPSHOT.jar
```
APP截图：

![APP截图][3]

原图：

![原图][1]

处理后图片:

![处理后图片][2]

隐藏文字：组织上已经决定了，今天的垃圾都归你
------

  [1]: ./static/yaofan.png
  [2]: ./static/yaofan_hide.png
  [3]: ./static/hide.png

