---
layout:     post                    # 使用的布局（不需要改）
title:      利用GitHub Pages搭建你的个人博客               # 标题 
subtitle:   theme provided by Hux 大佬 #副标题
date:       2018-07-15              # 时间
author:     YJC                      # 作者
header-img: img/方格取数.jpeg    #这篇文章标题背景图片
catalog: true                       # 是否归档
tags:                               #标签
    - 博客
    - GitHub
---

# 前言

很久很久（其实不久）以前，我在luogu的[杭州文澜中学团队](https://www.luogu.org/team/show?teamid=1214)看到了[memset0的博客](https://memset0.cn/)，便靠着**天才的大脑**，自己钻研，艰苦创业，从hexo到jekyll，从Typecho到WordPress，最终选择了GitHub Pages （随时随地有网就可以编辑），在一周前成功搭建了hzyangjc.github.io。本博客的主题由Hux大佬提供，同时感谢qiubaiying大佬的教程。
![][1]

# 准备
### 1. 注册GitHub账号
**[戳这里][2]**
![][3]
按你的实际情况填写即可。

### 2. fork我的repository
点击[这里][4]，进入我的仓库，点击右上角的fork，等一下，仓库就归你了。
![][5]

# 修改基础配置
### 1.点击进入repository的settings
将repository name改为“你的GitHub用户名.github.io”，点“rename”。
![][6]

### 2.回到Code
进入_config.yml,进行基础配置
![][7]
点击图中的那支笔，开始编辑
![][11]
按照边上的说明进行修改。

**注意**：第4行、15行的图片，需要上传。另开一个标签页，进入你的repository，进入img文件夹，点击有点智商就能找到的“upload files”，上传本地图片。
![][10]
这是gitalk配置。由于你是fork我的repo，不能使用，故全部注释掉（在前面加“#”）。
![][9]
改完后，来到页面下方，commit changes。
![][8]

休息一下，接下来是完善博客的步骤。


  [1]: https://i.loli.net/2018/07/15/5b4af4a7baa0c.png
  [2]: https://github.com/
  [3]: https://i.loli.net/2018/07/15/5b4af50238ec9.png
  [4]: https://github.com/hzyangjc/hzyangjc.github.io
  [5]: https://i.loli.net/2018/07/15/5b4afeea6c0fb.png
  [6]: https://i.loli.net/2018/07/15/5b4afeea6a9c6.png
  [7]: https://i.loli.net/2018/07/15/5b4afeea7c18b.png
  [8]: https://i.loli.net/2018/07/15/5b4b01c0071a9.png
  [9]: https://i.loli.net/2018/07/15/5b4b01c020b28.png
  [10]: https://i.loli.net/2018/07/15/5b4b01c0331ed.png
  [11]: https://i.loli.net/2018/07/15/5b4b01c029227.png
