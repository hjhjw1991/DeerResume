项目fork自 https://github.com/geekcompany/DeerResume 
原项目已经不再维护  
目前建议直接用他开发的新项目[冷熊简历](http://cv.ftqq.com)  
本项目留作个人用途及学习用  

*以下保留原fork项目的ReadMe*

---

DeerResume
==========

![img](http://www.jobdeer.com/img/rd.png)

好用的MarkDown在线简历工具，可在线预览、编辑、设置访问密码和生成PDF

  - 可自行搭建，任意修改页面样式和风格
  - 免安装，可放置于任何支持静态页面的云和服务器（当然包括GitHub
  - 在线MarkDown编辑器+实时预览
  - 在浏览器中实时保存草稿
  - 支持阅读密码，您可以直接将网址和密码发送，供招聘方在线浏览
  - 一键生成简单雅致的PDF，供邮件发送及打印
  

免部署的在线版本： → http://cvbox.sinaapp.com/

Demo → http://easy.digitcv.com/  

部署指南：→ http://get.jobdeer.com/745.get


教学：《如何写好一份技术简历》 → http://get.jobdeer.com/744.get

### FAQ

如何在没有云端的情况下使用DeerResume？

- 请在可访问云端的情况下完成MarkDown的编辑，然后复制好简历内容。
- 修改app.js 注释掉第3行，打开第4行，将数据源切到本地。 
- 修改data.php 填入标题和内容，并按自己的需要设置阅读密码。

---

*以上保留原fork项目的ReadMe*

在SAE上搭了一个简单的，自己的CV。看了DeerChen的部署说明好久都没弄好，点进去没有数据。无奈只好自己去看他的在线工具的内容，发现他有一步是生成自己的cv，我看了js发现这里会生成url和拉取默认数据，好嘛，我把这个js文件拿下来放到了sae上，然后检查了一下数据存放位置指向的确实是cvbox.digitcv.com。不知道中间哪一步起了作用，总之这样之后就可以看到和在线编辑数据了.

---

###update  

#### 2020-01-26
修改了托管的服务器和链接, 修改了生成pdf的api, 避免给原主人的服务器造成压力.  
[点击访问](https://cv.hjhjw1991.com) (暂未部署)

#### 2016-06-25

新浪云开始收费了，我比较穷，所以当时就停掉了原来的样例，但忘了来更新。大家可以在本地运行这个项目查看效果。
