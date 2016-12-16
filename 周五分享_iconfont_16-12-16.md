## Android 中使用`IconFont`

- ### `IconFont` 是什么？

  ​`IconFont`拆开来看，就是 Icon 和 Font，这样估计大家应该都能理解是什么，那两者结合呢？

  简单说，就是我们平时用的字体，不再是我们传统认知上的“文字”而是一个个的图标，

请看下图：

![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_1.png)****

这些图片对应的是字符编码，与文字类似。

- ### `IconFont`优缺点

  ​**首先**：它的体积要比图片小

![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_7.png)

一共34个图标，却只有16k ,平均一个图标不到0.5k

​	**其次**：具有更好的可维护性（因为是矢量图，所以拉伸不变形;颜色可以自行更换）

![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_2.png)

最后，不同平台的图片可以统一

但是，只支持使用单一颜色的矢量图，毕竟最后是转换成文字，只支持单一颜色

- ### 怎么得到或制作`IconFont`

1.登录 www.iconfont.cn 选择图片或者上传自己制作的矢量图

2.选择好自己想要的图标后 **下载代码** 

 ![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_3.png)

 

- ### 在android中使用

  第一步：复制字体文件![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_4.png)到项目 assets 目录；

  第二步： 打开下载文件中的![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_5.png)找到要使用的图片对应的编码

![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_1.png)

第三步：将`textView` 的字体设置为` iconfont.ttf`

第四步：对`textView` 赋值 如 上图中的 `smile` 图片对应的编码就是` /ue6af`

最后实现的效果如下图，

![img](https://raw.githubusercontent.com/CrazyRabbitCCC/share_android/master/image/iconfont_6.png)





 



