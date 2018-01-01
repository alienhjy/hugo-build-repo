+++
Tags = ['gitment', 'github', 'issues']
Categories = ['小事记']
title = "本博客的评论系统已经迁移到 Gitment"
date = "2018-01-01T18:29:00+08:00"
+++

之前本博客使用“多说”作为评论框，然而 2017 年 6 月 1 日起多说就已经无法使用。  
然后，作为懒人的我根本没去在意。。。直到最近闲mang着li无tou聊xian，就想着恢复博客的评论功能。

<!--more-->

******

在寻找多说评论框的替代品时，偶然看到了 [Gitment](https://github.com/imsun/gitment)，基于 GitHub Issues
的文章评论组件。  
（好吧，其实是一搜“多说”，到处都看到 Gitment [作者在安利 Gitment](https://www.v2ex.com/t/352545)，手动滑稽。）  

作为迁移的代价，以前存储在多说上的评论已经全丢了，真是对不起各位曾经在我这寒酸的博客下留言的大佬们（虽然没几个）。

其实本文就是一个免费广告，有兴趣的可以去给 Gitment 加一下星。  
至于安全性，我对于 web 还是不太懂，尽管作者说了使用 Gitment 时 OAuth
要求的大量权限是安全的，不过说实话强迫症看着还是很不开心，不知道 Github
啥时候能细分 OAuth 请求的权限。。。

对了，差点忘了说，在 Gitment 上评论需要登录你的 GitHub 帐号。

默认情况下，Gitment 不会初始化每个页面的评论功能（即打开对应的 Issue）， 
而是需要文章作者开启评论。   
所以并不会开启所有文章的评论，而是开启“大部分”文章的评论。  
**如果你希望某篇文章能开启评论以便交流，请在本文下留言。**