---
layout: post
title: "微信公众号稍后读前传之为什么"
date: 2014-06-15 10:01:04 -0400
comments: true
categories: [阅读推荐]
---

自从微信微信号推出以来，我的阅读源，尤其是新闻阅读源就从RSS转到了微信，详情可以参考我之前的博文[我的中文网络阅读源](http://yicunwendywu.github.io/cnblog/blog/2012/11/18/my-two-cents-on-chinese-internet-reading/)和[阅读推荐Vol. 2](http://yicunwendywu.github.io/cnblog/blog/2013/04/28/reading-recommendations-vol-2/)。公众号无疑给我来带了很多，随着我订阅的公众号数目的增多，我就发现了公众号阅读成为了痛点：
* 阅读体验糟糕：点击标题之后，要等很久才能加载好链接，之后还要忍受在手机小屏幕上阅读长文，并且，公众号“侵占”了我跟朋友的对话，为了解决这个问题，我重新注册了一个微信账号，从此用平板上的微信专门用来订阅公众号，后来，微信也发现了问题，推出了公众号折叠的功能。
* 不支持离线功能：由于我的阅读通常都发生在公共交通上，而我没有开通数据。为了解决这个问题，我每天都打开微信，把我感兴趣的文章复制链接，打开[Pocket](https://getpocket.com)，同意把链接加入Pocket，再在公共交通上打开Pocket阅读文章。
* 系统封闭之不支持分享到Pocket：本来加入Pocket的内容完全是可以通过安卓应用间分享完成的，由于缺乏这个功能，一个很简单的一步变成了让人抓狂的两步。
* 系统封闭之内容不开放：通常微信上的内容，如果作者（或某侵权者）不把它放到微信之外，没有订阅的人是看不到的。这一点我觉得是极其短见的。

于是下面给大家描述一下我痛苦的阅读流程：
1. 打开微信，进入所有订阅号
2. 打开某个有更新的公众号，并记住上面更新的数字（假设为n)
3. 从最后一篇开始倒数，并同时按照从n到1的顺序查看标题
4. 如果看到一篇感兴趣的题目，点击进入
5. 页面加载完成之后，点击右上角的点点点，点击复制链接
6. 用[Navigation Layer](https://play.google.com/store/apps/details?id=globe.trotter.gesture.overlay)打开Pocket，在这非常感谢Navigation Layer啊，没有了你我就要点击Home键然后点击Pocket图标。（能完成这个功能的app还有[SwipePad](https://play.google.com/store/apps/details?id=mobi.conduction.swipepad.android)，在此也表示非常感谢
- 打开Pocket之后，Pocket会提示是否将链接加入列表，点击同意
- 按返回键返回微信
- 按返回键返回订阅号的文章列表，并回想起之前的倒数（假设为m)
- 从这篇开始继续倒数，按照从m到1的顺序查看标题并从第四步开始重复

这个流程对于习惯了我在RSS浏览器中Next Page键不断的我来说，简直就是反人类。

2014年6月8日，我发布了解决我另一痛点的[RSS Subscriber](https://rsspocket.parseapp.com/)，不久后搜狗公众号搜索推出了，看到这个极好的机会，我在RSS Subscriber代码的基础上进行了快速的修改，终于在6月12日发布了[微信公众号稍后读](http://wechatpocket.herokuapp.com)，从此我的公众号订阅微信号就退休了，我的心情也从此舒畅了很多。（当然了，目前还要追捕不少bug。）

在此再一次欢迎大家，尤其是使用微信公众号的大家来使用[微信公众号稍后读](http://wechatpocket.herokuapp.com)，因为我真心希望这个app可以帮助更多人把时间花在阅读而不是在点击操作上，让阅读成为一种习惯而不是一种负担。同时我也非常欢迎大家的各种反馈。
