---
title:  如何在Vercel部署一个自己的蔚蓝档案Blog
date: 2024.6.23
tags: [教程, 建站,蔚蓝档案,Vercel,Vitepress]
---

这篇文章将会教你如何在Vercel部署一个属于自己蔚蓝档案主题的Blog

---

## 一,简要
你需要:  
一台能正常访问互联网的 **电脑/手机**  
一个代理(非必要)  
一个 **Github账号**  
一个 **Vercel账号**  
一双灵活的手  

准备好这些东西后 Let's Start!

## 二,教程
考虑到大部分人群用的都是移动端  
所以以下教程全程使用**手机**演示操作  
下面使用了via浏览器  
1.使用Github项目(请确保你登录了你的账号)  [vitepress-theme-bluearchive](https://github.com/Alittfre/vitepress-theme-bluearchive)<br />进入后点击上面绿色的 **"Use this template"** 后选择 **"Create a new respository"**  
如果可以还请各位给原作者点个Star
![位置如图所示](https://img.picui.cn/free/2024/06/23/6677f0e27fdb1.jpg)

2.创建一个仓库<br />
在 **"Repository name"** 里输一个你想要的仓库名称
**"Description"** 为仓库简介 非必填  
仓库类型选择 **"Public"** <br />
如果你不想让别人看到你的仓库里面有什么  
那就选 **"Private"** <br />
选好之后 **"Create repository"**  
创建完成会自动跳转至仓库首页
![如图](https://img.picui.cn/free/2024/06/23/6677f0e28071e.jpg)

3.部署到Vercel
打开[Vercel](vercel.com)官网(请确保你登录了Vercel账号)  
点击 **"Overview"** 界面右上角的 **+** 号  
选择 **"Project"** 以创建一个项目
![如图](https://img.picui.cn/free/2024/06/23/6677f0e50f239.jpg)  
如果你绑定了你的Github账号你会看到账号下的仓库列表  
这里选择我们在2.创建的仓库并点击 **"import"**  
此处我选择我临时搭建的test仓库进行演示
![Screenshot_2024-06-23-17-22-32-538_mark.via-edit](https://img.picui.cn/free/2024/06/23/6677f0e455dc1.jpg)  
接着在跳转的网页里我们把右边的按钮打开  然后在把 **"Output Directory"** 的内容改成 **".vitepress/dist"**  
最后点击下方的 **"Deploy"** 等待一会构建完成  你会看到一个大大的Hello Sensei!  会有一串烟花庆祝你已经成功部署到Vercel了  
![IMG_20240623_173547](https://img.picui.cn/free/2024/06/23/6677f0e27bbfa.jpg)  
然后我们点击 **"Continue to Dashboard"** 到项目管理面板  
到这里Vercel的部署就完成了 如果你想绑定自定义域名你可以看看这里[解决 Vercel 部署网站在国内被墙](https://blog-zoey.top/posts/vercel-dns-china)  
顺便说一句 如果使用了cloudflare绑定域名 你可能还需要将SSL安全设置改成 **完全** 而不是 **完全(严格)**


4.在Github修改Blog配置文件
这里我们返回我们搭建的Github仓库
![IMG_20240623_141959](https://img.picui.cn/free/2024/06/23/6677f0e6284f8.jpg)  
注:  
> vitepress是主题和配置文件目录  

> posts是文章目录(markdown)  

> public是附件目录  

> tags是标签目录  

在.vitepress/里找到**config.mts** 并打开编辑
![IMG_20240623_142322](https://img.picui.cn/free/2024/06/23/6677f0e57da70.jpg)  
这里的配置看个人喜好  大家可以在作者的[README](https://github.com/Alittfre/vitepress-theme-bluearchive/blob/main/readme.md)里查看编写格式  

## 三,结语
各位老师们学会了嘛  
有问题欢迎在下面的评论区讨论哦  
最后  
Blue Archive 启动！
![Image_1719136345022](https://img.picui.cn/free/2024/06/23/6677f0e26c4fb.png)













