---
author: 公子小白
pubDatetime: 2023-12-24T21:30:00Z
title: 大事件，博客在 Github Page 复活！
postSlug: "47"
featured: false
draft: false
tags:
  - 日志
  - 博客self
description: 复活！原博客 randomwalk.top 迁移到 Github Page，舍弃 WordPress，powered by Astro 和 AstroPaper。又一次博客大事件！
---

这个周末折腾了两天，终于把博客重新建立起来了。

不过，在此之前先得说说之前的站点 randomwalk.top 怎么了？

由于这个域名比较便宜，我今年年中一次续了三年的费用，所以域名现在还保留着。但是从十月底开始，我决心不再续费腾讯云的云服务器，所以站点自那之后就无法访问了。毫无疑问，从我毕业以后的超低更新频率来看，每月支付 70 元左右的服务器费用算是一笔奢侈的开销（10 月份还终于把 PGP 的续费给停了，自动续费真是太可怕了！！！）。迁移博客是件还挺麻烦的事情，因此，我虽然早有此意，但一直都因为懒惰而无法下定决心。于是只好选择不破不立的道路，先别从我卡里划钱再说（笑😂）。

最初的计划是迁移到腾讯云的轻量级应用服务器，每月的成本大概不到 30（虽然也不低了），依然采用 WordPress。但是 WordPress 对于博客来说，已经是上个时代的软件了：虽然插件丰富，但我早就对它的臃肿颇有怨言；虽然后台编辑器支持的样式不少，但代价就是不完全兼容 MarkDown，而且对公式的支持很不优雅——这也造成了本次迁移的主要成本。况且，WordPress 对新人友好虽然是我当年选择它主要理由，现在这一优势也无意义了。

恰好，在 10 月份左右，我开始关注 JavaScript 和 TypeScript 的技术栈和开源库（其实工作原因早就该关注的），注意到了 [Astro](https://github.com/withastro/astro) 这个项目，觉得很有意思，便逐渐开始学习，也正好慢慢弥补我 html 和 CSS 等前端技术的缺失。了解之后发现使用 Astro 搭建博客有几项极吸引我的优势：

1. 完全支持 MarkDown 语法——这意味着通用性，以后想要迁移（折腾）极为简单
2. 对 MarkDown 格式公式仅仅需要简单几步即可完成——简单且优雅
3. 静态网站，加载速度快，完全可部署在 Github Page 上——完全无成本！
4. 使用过程中可进一步熟悉 Astro 及其相关技术栈——全栈！全栈！全栈！
5. 相比于 WordPress 的 php，Astro 的 Js 或 Ts 更让我有自定义的欲望······

但是这一次迁移不同于以往换域名或者换服务器，由于底层软件的更换，是痛苦的。最大的损失就是为数不多的珍贵评论目前没有迁移过来（新博客采用了 [giscus](https://github.com/giscus/giscus)）——许多人的留言曾是支持我维护这个博客的动力，而且 GitHub Page 和 giscus 本身就会带来一些访问量和互动量的障碍。其次原来的文章有一百多篇，目前仅迁移过来 47 篇，以后可能会有少量的迁移，但不会太多——并非技术上做不到，而是我故意为之：我保留了大部分的日志和大约半数的经济学笔记，但舍弃了许多计算机相关的笔记：作为一个 GPT 的重度用户，当我如今重新审视自己曾经的技术笔记时，我不由得思考它们在现在究竟价值几何？——它们大多无非是一些简单经验的总结、新接口的使用备忘、甚至有一些原创性并不高的内容。在如今的时代，都不需要 Google，GPT 两行对话就能解决的问题，我自己都不会再为此翻看笔记了。相反，日志或读书笔记作为一种生活的记录和感受，尽管流水账、矫情、无趣、幼稚，但是每每翻看那些生活的记录，不论是快乐的还是沮丧的，都十足珍贵且无可替代——这大概是我与 AI 对抗的方式，希望以后能多写日志和读书笔记。

当然，这个站点还有些要完善的地方，比如说：

1. randomwalk.top 这个域名是否要重定向到这个 ip？
2. 应该使用 giscus 作为评论区的最终方案吗？
3. 图床怎么办？腾讯云剩余的一点钱要不要用来做对象存储？
4. 甚至新页面的建设等等······

种种问题都最好能用最小的成本达到最大的收益吧。我显然没以前那么爱瞎折腾了~~
