---
layout: article
title:  "css实现响应式全屏背景"
date:   2018-1-3
categories: posts_rwd
image:
  teaser: CSS.jpg
  
---

#### css实现响应式全屏背景
利用css中 background-size：cover  填充整个viewport。
注意：一张背景图像素5000px*5000px在pc端，缩放都基本满足要求 不会出现模糊失真；但是在移动端使用如此大的图片完全是浪费资源，大图会导致加载变慢，尤其是在移动网络下。

body{
/* 加载背景图 */
background-image: url(images/background-photo.jpg);

/* 背景图垂直、水平均居中 */
background-position: center center;

/* 背景图不平铺 */
background-repeat: no-repeat;

/* 当内容高度大于图片高度时，背景图像的位置相对于viewport固定 */
background-attachment: fixed;

/* 让背景图基于容器大小伸缩 */
background-size: cover;

/* 设置背景颜色，背景图加载过程中会显示背景色 */
background-color: #464646;
}




@media only screen and (max-width: 767px) {
  body {
    background-image: url(images/background-photo-mobile-devices.jpg);
  }
}
