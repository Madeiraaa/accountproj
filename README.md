**学号：16340175**

**姓名：欧友特**

---

## 一、我的账簿小程序概况
### 1. 小程序简介

我的账簿主要面向喜爱记录自己日常开销的人们，以微信小程序的方式展现，主打方便快捷，打开微信随手即可记录。定位位置，旅行足迹等功能，不止显示了冰冷的数字，而是试图通过消费，尽可能生动地记录用户的行程。


### 2. 目标用户&用户需求

目标用户：主要面向学95后学生

用户需求：

a. 必要型需求：记录日常生活开销

b. 期望型需求：详细的消费类型、消费备注

c. 兴奋性需求：记账定位，可以生成消费轨迹；生成消费统计图


### 3. 产品亮点

记账可以随手定位，用户可以生成属于自己的消费轨迹图，以另一种方式记录自己的生活。

生成消费统计图，用户可以直观的了解到日常开销的占比。


### 4. 运行环境

前往小程序官方网站下载【微信开发者工具】

[https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)

安装成功并登陆后，选择小程序-倒入项目，选择下载下来的代码包目录，用自己的Apple ID或使用测试号，即可成功运行小程序。

【提示】需要将project.config.json文件里的appid更改为自己的app id

![图片](https://uploader.shimo.im/f/OvnQZnI5zjs2ip4j.png!thumbnail)


运行页面

![图片](https://uploader.shimo.im/f/Bcf9Ciyl9vU1dIXH.png)


## 二、小程序结构图
![图片](https://uploader.shimo.im/f/3SbdR6hdDhkQoZUm.png)


## 三、小程序展示
### 1. 小程序首页

在首页可以新建一个账目

如图所示，账目名称为日常开销。

![图片](https://uploader.shimo.im/f/j7gYBaIBLywGG5OH.png!thumbnail)  ![图片](https://uploader.shimo.im/f/4ElMuCyeMmUYp2sm.png!thumbnail)  ![图片](https://uploader.shimo.im/f/3WZUsLKmA1Qb5ih9.png!thumbnail)

账目名称栏左滑可以实现重命名或删除操作

![图片](https://uploader.shimo.im/f/ouG052D4ICYmGn8z.png!thumbnail)


### 2. 开始记账

![图片](https://uploader.shimo.im/f/LOskAZmfUmsd1dSE.png!thumbnail)  ![图片](https://uploader.shimo.im/f/IIjP6SfQjNoyTmCT.png!thumbnail)  ![图片](https://uploader.shimo.im/f/rYCenfEV9gMEMESU.png!thumbnail)

账单列表，左滑即可实现删除：

![图片](https://uploader.shimo.im/f/fBtSI7wkWsM2J6XN.png!thumbnail)  ![图片](https://uploader.shimo.im/f/ovHiOuvmEU804ET2.png!thumbnail)  ![图片](https://uploader.shimo.im/f/m6uhnavLtS4ixBoz.png!thumbnail)

点击图表图标，即可生成消费统计图和消费轨迹图。

点击统计图会出现同一类别下的账单详情：

![图片](https://uploader.shimo.im/f/Yax8fq0zRGQUjab5.PNG!thumbnail)  ![图片](https://uploader.shimo.im/f/LpMGSq4wjzgUpI83.PNG!thumbnail)


### 3. 设置界面

可以设置账目分类，新增账目分类：

![图片](https://uploader.shimo.im/f/GDvZ8AuiDGcAz0lU.png!thumbnail)  ![图片](https://uploader.shimo.im/f/oqpSd3PElMYouann.png!thumbnail)  ![图片](https://uploader.shimo.im/f/j65y8trJ540MdD4k.png!thumbnail)

左滑实现单个类别删除操作，点击垃圾桶图标即可实现自建类别一键删除：

![图片](https://uploader.shimo.im/f/jWdHNQB3slUUgRAG.png!thumbnail)  ![图片](https://uploader.shimo.im/f/f8gRZdE9CGEnpopr.png!thumbnail)

