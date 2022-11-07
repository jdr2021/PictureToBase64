# PictureToBase64
图片转base64，方便写博客，引入图片资源，避免图片资源丢失。

# 更新日志：2022-11-7
由于之前有人直接拿我博客的截图去发了原创文章，因此工具增加了水印功能。

<img src="https://github.com/jdr2021/PictureToBase64/blob/master/1667804430181.jpg">

<img src="https://github.com/jdr2021/PictureToBase64/blob/master/1667804536256.jpg">

# 更新日志：2021-11-9
## 使用方法
运行jar包，然后使用微信截图，点击按钮“从剪切板读取并转换”

<img src="https://github.com/jdr2021/PictureToBase64/blob/master/1662912535585.jpg">

然后粘贴到md的编辑器中，即可。

## 输出格式
```
![image][link1]

[link1]:data:image/png;base64,image_base64
```

# 优势
通过此方法加载文件，可以避免图片资源丢失

# 劣势
会导致md文件过大，一般写完blog，md文件大小会普遍在2m-4m。



# 特别感谢
感谢这位作者的工具提示。
QT5的工具dll文件太大，因此我就自己尝试用java写了一个。
https://github.com/SnowFairyStory/PictureBase64Encode


