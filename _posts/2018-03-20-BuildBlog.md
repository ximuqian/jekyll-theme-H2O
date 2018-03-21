---
layout: post
title:  使用Github Page搭建属于自己的Blog
date: 2018-03-20
categories: 教程
tags: 教程
---
![A434EAEB-5CAA-413B-A63F-7C060691234287e40.png](https://miao.su/images/2018/03/20/A434EAEB-5CAA-413B-A63F-7C060691234287e40.png)
# 使用Github Page + Jekyll搭建属于自己的Blog
## 牛刀小试
从2017年暑假看过[黄玄大大](http://huangxuan.me)的Blog之后，萌生了一个想制作一个**属于自己的BLog**的想法。可是我又是一个非计算机专业的学生。其实蛮无奈的，很多东西并不是很懂，特别是代码方面。经过一段时间的学习之后，利用这点**皮毛知识**终于是搭建成功一个**属于自己的Blog**了。

# 准备阶段
---
## 环境配置
* 运行环境 MacOS 10.12.6 _windows环境也可使用相同方法 如有疑问请邮件联我的[邮箱](mailto:lxzrj@foxmail.com)
* 略懂英语（初中水平即可）涉及Github.com的使用
* 看的懂汉字即可
* 百度并学习[Markdown语法](https://www.appinn.com/markdown/) 本篇博文使用Markdown书写
 
 
 看起来是不是很简单呢？其实吧，就是那么简单的东西，在毫无基础的我眼里其实蛮麻烦的。现在我就以我最大的能力，以及最简明的语言来帮助大家创建一个属于自己的Blog。
 

---
# 第一步-购买域名并注册GitHub
 ***域名***，相信大家并不陌生比方说**www.baidu.com**就是一个域名，它相当于一个网络世界的**身份证**，而我们第一步当然是要弄一个网络的身份证啦。与现实中不一样，域名并不是免费申请的，而是需要自行购买的。（捂脸逃）
 
 ***GitHub*** ，我们主要是利用***GitHub Page*** 可以简单理解为GitHub page就是一个服务器 而服务器就相当于一个你在网络的家，而服务器一般不便宜，特别是阿里云和腾讯云的服务器，而且国内的服务器全部都是需要备案的，并且需要掌握一定的***linux***知识。所以，这时候GitHub站出来了，GitHub真的是一个属于全人类的好网站（还有国内的coding 还有一个Hub PXXnHub 嘿嘿嘿 ）GitHub不需要备案，也没有什么限制。对于写个人Blog是绝对够的。
 
域名购买注意事项：

* 首选选用与你有关，并且好记的域名样式，但是也不要太好记 比方说360.com（如果你是土豪，就当我没说）
* 怕麻烦请勿使用***.CN结尾的域名，因为天朝需要备案。而且时间不短

推荐**两个安全的域名购买地点**
```
GOdaddy.com 
```
```
wanwang.aliyun.com
```

接下来一切都是按照程序走，买好域名先放在一边不用管他。域名大约几块钱到无上限不等，我们普通的域名，比方说我在万网买的```.xin```域名是20多块钱一年。（这是在第一年拥有优惠的情况下，之后估计要几百块钱一年）

***GitHub.com*** 这个网站对于学习计算机的同学应该不陌生吧。是一个代码托管网站。简而言之就是全世界的程序员，都可与你在一起工作，一起解决问题。

* 第一步 注册GitHub，这个我就不介绍了。GitHub没有中文，请使用你的初中英语水平即可
* 第二步 搜索并fork一个你喜欢的Jekyll theme，推荐一个[Jekyll theme web](http://jekyllthemes.org)找到之后点击GitHub的标志，然后fork到自己的 Repositories
* 第三步 阅读你fork的Jekyll theme 中的 ***README*** 查看作者对这个主题的讲解
* 第四步 点击Settings - GitHub Pages - Source - master branch - 点击save - Choose custom domain - 输入你刚刚买的域名

到这为止，你已经完成了百分之80%了

***

# 绑定域名 

接下来就是将你的域名***绑定***至你的GitHub Page。

第一步 获取你的GitHub Page IP 

windows 获取方法

* 微软徽+s 搜索 CMD输入以下代码

<pre><code>ping github.com/XXX
</code></pre>

XXX为你的用户名。
这时候我们就可以获得一个IP，这就是你的GitHub Page IP