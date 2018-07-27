**欢迎回来！继续搭建你的个人博客**
# 修改about.html
图中的内容，按照你的情况填写即可。
![](https://i.loli.net/2018/07/26/5b597a78c7088.png)
 
**拖到右边**：
 
![](https://i.loli.net/2018/07/26/5b597b113c3e4.png)

会HTML的大佬可以发挥。
# 修改package.json
不放图了，反正前三行自己改
# 修改座右铭
进入`index.html`，第三行的description就是了（引号不能删掉，下同）
# 修改README.md
用markdown语法自由改，就是GitHub上的介绍。
# 发布新文章
- 进入`_posts`文件夹,点击`create new file`：

![](https://i.loli.net/2018/07/27/5b5adebad9584.png)
 
- 在上面的`name your file...`中，填写格式为`年-月-日-名称.md`，如图；然后用[GitHub的markdown语法](https://www.cnblogs.com/yabin/p/6366151.html)写文章。链接中的博文未提到的是markdown图片的插入方法：`![图片介绍](图片网址)`。这里就不得不推荐一个好用的图床，可以给本地图片一个专属网址：[sm.ms](https://sm.ms/)

![](https://i.loli.net/2018/07/27/5b5ae0cf75daa.png)
 
- hold on：文章基本设置
就是如图这玩意：

![](https://i.loli.net/2018/07/27/5b5ae355ae8d1.png)

格式：
```
---
layout:     post                    # 使用的布局（不需要改）
title:      方格取数               # 标题 
subtitle:   NOIP2000提高组第四题 #副标题
date:       2018-07-09              # 时间
author:     YJC                      # 作者
header-img: img/方格取数.jpeg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - 信息学
    - NOIP
---
```
其中`header-img`这里用的是GitHub repository中的图片，需要upload files。至于如何，在利用GitHub Pages搭建你的个人博客（上）中已讲过。
