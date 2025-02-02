---
title: 尝试找回用过PS的记忆
excerpt: 混账，你学了甚麽
date: 2025-01-24 17:17:44
updated: 2025-01-24 17:17:44
categories:
  - 闲谈
  - 折腾
published: true
poster:
  headline: 尝试找回<br>用过PS的记忆
  caption: 2025.01.24 <br> 混账，你学了甚麽！？
  color: 
tags:
  - 闲谈
  - 折腾
  - PS
  - PhotoShop
cover: https://pic1.imgdb.cn/item/67948540d0e0a243d4f7bfad.jpg
banner: https://pic1.imgdb.cn/item/67948540d0e0a243d4f7bfad.jpg
comments: 
indexing: 
breadcrumb:
---
>混账，你这在学校学了甚麽！？

# 重拾 PhotoShop 的原因

很简单，因为开始重新写起了博客，想着直接做一套封面模板来应对以后的 banner 图制作，于是乎，打开PS开始重拾。

# 霍，这啥来着？

量好需要的图片的尺寸，打开 PhotoShop ，通过尺寸创建，建好后自动打开工程项目一气呵成，

然后就是对着工作区发呆。

![67938a4dd0e0a243d4f7a1ca.png](https://pic1.imgdb.cn/item/67938a4dd0e0a243d4f7a1ca.png)

我要干什么？干啥来着？
发呆无用，先把图片扔进去。

## Banner 背景模糊

我使用的博客的主题在默认情况下支持将标题显示位置调整在banner的左上角或者左下角，所以只有右侧是可以展示图片的位置。

![67938a7dd0e0a243d4f7a1d9.png](https://pic1.imgdb.cn/item/67938a7dd0e0a243d4f7a1d9.png)

外加上我对高斯模糊有一定的执着，要作为 banner 图使用的图片肯定会放在最底部图层做个铺底&模糊。

![alt text](https://pic1.imgdb.cn/item/6794394fd0e0a243d4f7afad.png)
![alt text](https://pic1.imgdb.cn/item/679439c1d0e0a243d4f7afaf.png)

事先使用表面模糊铺底之后再使用高斯模糊滤镜，但看起来还是有点缺少高级感？可以添加少量的杂色让高斯模糊的质感更好。

![alt text](https://pic1.imgdb.cn/item/67943fd6d0e0a243d4f7b086.png)

现在看起来就像毛玻璃一样了，背景模糊的处理就算是完成了。

## Banner 主图处理

先把图扔进去,并且在外面套两层的组，

![alt text](https://pic1.imgdb.cn/item/67944cccd0e0a243d4f7b2b5.png)

在组1上添加蒙版，并且涂黑需要遮挡的部分，

![alt text](https://pic1.imgdb.cn/item/67944d7dd0e0a243d4f7b2c5.png)

初具雏形了，但因为图层之间没有阴影，看起来会有点欠缺层次，解决起来很简单，只需要右键点击图层列表中的组2，打开混合选项，并打开投影效果，看效果调一调。

![alt text](https://pic1.imgdb.cn/item/67944f64d0e0a243d4f7b2f5.png)

最后的成果也就是这个样子了。

![alt text](https://pic1.imgdb.cn/item/679450b8d0e0a243d4f7b322.png)

# 后记
后面的模糊背景也可以根据对文字的影响情况来调整亮度、饱和、对比度。

将蒙版和混合效果放在外层的“组”中的原因很简单，因为这个工程文件我是作为“模板”来使用的。
而如果直接将蒙版和混合效果放置在图片图层上的话，在替换图片时会导致图像画布大小变更，最后导致原来的蒙版对不上原来的大小。
这对于模板而言是极大的增加了麻烦程度的