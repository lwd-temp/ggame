---
title: Gitee
description:
published: true
date: "2024-05-08T23:57:29"
特殊标签标记: #无标签
editor: markdown
dateCreated: "2022-05-19T18:11:45"
---

## 简介

<ruby>Gitee<rt>码云</rt></ruby> 是基于 Git 的代码托管和协作开发平台，由开源中国于 2013 年推出，主要模仿的是 [GitHub](/website/GitHub.md)。[^71707213]

[^71707213]: 《[Gitee](https://zh.wikipedia.org/w/index.php?title=Gitee&oldid=71707213)》, 维基百科. 2022-05-19. 参照: 2022-05-19. [Online].

## 强制私有 codes

Gitee 曾有个 codes 功能，类似于 GitHub Gist，能创建代码片段并公开分享，URL 大概是 `https://gitee.com/example_name/codes/example_id/raw`/。[^97299]

[^97299]: HelloGithub, 《[mac安装homebrew失败怎么办？](https://web.archive.org/web/20220518144639mp_/https://www.zhihu.com/question/35928898/answer/924797299)》, 知乎, 2020-05-08. (参照 2024-05-08).

2022 年之前的某个未知时间，Gitee 将所有的 codes 代码强制非公开化了，导致一些安装脚本不能使用。[^1315] 

[^1315]: HelloGithub, 《[如何看待 5 月 18 日 Gitee 仓库开源须审核，已开源部分仓库暂时关闭，审核通过后再次公开？](https://web.archive.org/web/20220518144607/https://www.zhihu.com/question/533388365/answer/2491315574)》, 知乎, 2022-05-18. (参照 2022-05-19).

## 仓库公开须知

2022年1月17日 之前的未知时间，[^I4R31X] Gitee 添加了「仓库公开须知」的协议，需要同时勾选三个协议，才能将仓库设置为公开仓库。详细内容如下：[^93931]

[^I4R31X]: cvicse004861, 《[私有仓库转公开仓库时没有仓库公开须知 · Issue \#I4R31X](https://web.archive.org/web/20220519163229/https://gitee.com/oschina/git-osc/issues/I4R31X)》, Gitee, 2022-01-17. (参照 2022-05-20).

[^93931]: 山外的鸭子哥, 《[码云(Gitee)宣布托管开源项目先审后发 承诺合法无违规经人工审核后才可访问](https://web.archive.org/web/20220519165657/https://www.landiannews.com/archives/93931.html)》, 蓝点网, 2022-05-19. (参照 2022-05-20).

> [!quote]+ 仓库公开须知
>
> +   [ ] 我承诺此仓库内容不违反任何国家法律法规
> +   [ ] 我承诺此仓库内容不侵犯任何单位及个人的版权和权益
> +   [ ] 我承诺本人拥有该仓库所有内容的版权；如仓库内容引用他人作品，我承诺所引用内容均确认为合法内容, 不存在版权问题，且对引用内容做了详细标注说明
>
> 如违反以上承诺，Gitee保留追究相关责任的权利。更多信息请访问《Gitee.com网站使用条款》

2022年5月18日，需要签署「仓库公开须知」协议，并等待审核，仓库才能公开。如果没有审核，仓库就会强制处于私有状态，访客查看会显示「为了营造绿色健康的开源社区，推动中国开源生态建设，当前仓库仅限成员访问。」[^88365]

[^88365]: 野蕨菜, 《[如何看待 5 月 18 日 Gitee 仓库开源须审核，已开源部分仓库暂时关闭，审核通过后再次公开？](https://web.archive.org/web/20230127115908/https://www.zhihu.com/question/533388365)》, 知乎, 2022-05-18. (参照 2024-05-08).

## 禁止图床

2022年3月25日，Gitee 对仓库中的图片添加了禁止其他网页查看仓库中的图片的机制，[^z1][^z2][^z3][^z4][^z5] 并且有人发现了网站发生了变化，从命令行访问会产生一个过渡页面，需要跳转一下，这导致命令行安装软件脚本不再正常工作。而且导入 Github 仓库到 Gitee 时也不能直接选择「公开」仓库， 需要在设置里同意「仓库公开须知」才能公开。[^2409]

[^z1]: 《[如何看待使用gitee大量屏蔽外链，之后不能在继续做图床了，对大家的影响大吗，这种情况会持续多久？](https://web.archive.org/web/20220509162157/https://www.zhihu.com/question/524089317)》, 知乎, 2022-03-25. (参照 2022-05-20).

[^z2]: 《[有什么好用的图床推荐，gitee图床挂了吗？](https://archive.is/CONTD "https://www.zhihu.com/question/524094354")》, 知乎, 2022-03-25. (参照 2022-05-20).

[^z3]: 《[gitee图床是加了防盗链吗？我图片302重定向到gitee的默认图标了 ?](https://web.archive.org/web/20220514101652/https://www.zhihu.com/question/524099214)》, 知乎, 2022-03-25. (参照 2022-05-20).

[^z4]: 《[如何看待开源中国Gitee在不通知用户的情况下突然禁止图床外链访问，导致用户权益受损的行为？](https://web.archive.org/web/20220329035405/https://www.zhihu.com/question/524345403)》, 知乎, 2022-03-27. (参照 2022-05-20).

[^z5]: itemqq, 《[gitee 把图床 ban 掉了？](https://web.archive.org/web/20220326011741/https://www.v2ex.com/t/842932)》, V2EX, 2022-03-25. (参照 2022-06-30).

[^2409]: Jeff Tian, 《[如何看待开源中国Gitee在不通知用户的情况下突然禁止图床外链访问，导致用户权益受损的行为？](https://web.archive.org/web/20220519161838/https://www.zhihu.com/question/524345403/answer/2409484751)》, 知乎, 2022-03-27. (参照 2022-05-20).

在 Gitee 的《网站使用条款》中，确实明确的写出了「禁止盗链 奥思网络禁止擅自利用本网站内容的网页构架系统的行为。奥思网络保留断开任何未经授权指向本网站的超文本链接或网页构架系统的权利。」[^gitee_terms]

[^gitee_terms]: 《[网站使用条款](https://web.archive.org/web/20180316222901/https://gitee.com/terms)》, Gitee. (参照 2022-06-30).

## 「AV」审查

2022年5月19日，知乎用户「王德福」讲了个笑话：[^533388365]

[^533388365]: 王德福, 《[如何看待 5 月 18 日 Gitee 仓库开源须审核，已开源部分仓库暂时关闭，审核通过后再次公开？](https://web.archive.org/web/20220519131519/https://www.zhihu.com/question/533388365/answer/2492549159)》, 知乎, 2022-05-19. (参照 2022-07-05).

> [!quote]+ 王德福的知乎回答
>
> 本次提交代码中：
>
> ```text
> // user.vue line:87
>
> const saveData = () => {
> ```
>
> 因包含敏感词 **av**，本次PR被拒绝，建议修改后再尝试提交。
>
> 感谢您的理解。
>
> Gitee 审核团队

随后被不规范转载，导致一些人误以为这是真实的系统消息。[^5371]

[^5371]: xiaozhch5, 《[Gitee代码提交需谨慎，代码中含有save也被拒绝](https://web.archive.org/web/20220705072105/https://lrting.top/qapress/5371.html)》, 从大数据到人工智能, 2022-05-20. (参照 2022-07-05).

随后在 2022年6月2日，Gitee 背后的开源中国公司开设了直播，节目中指出了这个消息是虚假的，并称：「发布这个消息的作者也已经跟我们道歉了，这纯粹就是他个人因为好玩发的调侃。」[^5534534]

[^5534534]: OSCHINA编辑部的个人空间, 《[险被 GitHub 收购？近期审核风波？Gitee 创始人出面回应](https://web.archive.org/web/20220705004616/https://my.oschina.net/oscpyaqxylk/blog/5534534)》, 中文开源技术交流社区, 2022-06-02. (参照 2022-07-05).

不过从 2022年6月 开始，有人发现 Gitee Pages 会审查词语：[^I5EYEC]

[^I5EYEC]: 大风和豆腐干, 《[为啥我写个文章都违规了](https://web.archive.org/web/20220704145036/https://gitee.com/oschina/git-osc/issues/I5EYEC)》, Gitee, 开源中国/Gitee Feedback, Issue \#I5EYEC, 2022-06-30. (参照 2022-07-05).

![大风和豆腐干的gitee截图](https://s3.tebi.io/ggame/website/gitee/大风和豆腐干的gitee截图.webp)

原因是关键词审查（敏感词），至少会审查这些内容「s**av**e」「以**下注**意」「在手机**上访**问」，这些文字的加粗部分就是关键词。[^I5F3YL][^864017]

[^I5F3YL]: Think, 《[index.html包含敏感词](https://web.archive.org/web/20220704194506/https://gitee.com/oschina/git-osc/issues/I5F3YL)》, Gitee, 开源中国/Gitee Feedback, Issue \#I5F3YL, 2022-07-01. (参照 2022-07-05).

[^864017]: realpg, 《[在 gitee，你的代码里不能包含 SAVE。。。](https://web.archive.org/web/20220705000050/https://www.v2ex.com/t/864017)》, V2EX／[水深火热](/website/V2EX.md#水深火热), 2022-07-04. (参照 2022-07-05).

这些针对 Gitee Pages 的审查，能追溯到 2022年5月：

> [!abstract]+ 一些关于 Gitee Pages 的审查情况
>
> 1.  《[搜索「违规」](https://web.archive.org/web/20220705073104/https://gitee.com/oschina/git-osc/issues?issue_search=违规)》, 2022-07-05. (参照 2022-07-05).
> 2.  get2bad, 《[gitee pages审核总是违规，纯技术博客，有什么问题嘛？](https://web.archive.org/web/20220705075323/https://gitee.com/oschina/git-osc/issues/I4NL8O)》, 2021-12-22. (参照 2022-07-05).
> 3.  oxygen, 《[README 违规，但没显示违规原因](https://web.archive.org/web/20220705075330/https://gitee.com/oschina/git-osc/issues/I57GY8)》, 2022-05-15. (参照 2022-07-05).
> 4.  Chuanzhen He, 《[部署失败，无违规信息，却仍然显示部署失败？](https://web.archive.org/web/20220705072942/https://gitee.com/oschina/git-osc/issues/I5AFHO)》, 2022-06-01. (参照 2022-07-05).
> 5.  xwxone, 《[可能包含违禁违规内容，请排查调整后再行重试](https://web.archive.org/web/20220705075130/https://gitee.com/oschina/git-osc/issues/I5AORE)》, 2022-06-04
> 6.  大白鹅, 《[gitee page 部署失败，提示违规，不清楚哪里违规了](https://web.archive.org/web/20220705074958/https://gitee.com/oschina/git-osc/issues/I5B1KW)》, 2022-06-07. (参照 2022-07-05).
> 7.   andy, 《[【gitee page 部署失败】可能包含违禁违规内容，请排查调整后再行重试。](https://web.archive.org/web/20220705072852/https://gitee.com/oschina/git-osc/issues/I5BI39)》, 2022-06-09. (参照 2022-07-05).

还有未知时间，遇到「左倾」「右倾」这样的关键词，就会直接封锁 Gitee Pages 功能。[^88259]

[^88259]: JasonkayZK, 《[当年gitee pages的博客因为写了篇红黑树，里面带了“左倾”、“右倾”这两个字导致整个博客被封之后就再也没用过gitee了，哈哈😄](https://web.archive.org/web/20220519143836/https://twitter.com/Jasonkay_ZK/status/1527297310811488259)》, Twitter, 2022-05-19. (参照 2022-09-22).

## Gitee Pages 关闭

最早在 2024年4月29日，有人发现 Gitee Pages 功能下线，相关按钮变成灰色，无法开启仓库的 Gitee Pages 功能。[^2-446]

[^2-446]: VibMike, [Screenshot_2024-05-01-14-50-02-446_com.tencent.mm-edit.jpg - VibMike/AboutGiteePages](https://web.archive.org/web/20240506155425/https://gitee.com/VibMike/about-gitee-pages/blob/master/Screenshot_2024-05-01-14-50-02-446_com.tencent.mm-edit.jpg), Gitee, 2024-05-01. (参照 2024-05-08).

稍后有人向客服询问：

+   2024年4月30日 客服说：「不着急」。[^2-446]
+   2024年5月1日 客服说：「下线了」。[^2-446]
+   2024年5月6日 客服说：Pages 服务短期内大概率无法上线了。[^9L5FJ]

[^9L5FJ]: VibMike, 《[关于GiteePages无法启动和更新的看过来！ · Issue #I9L5FJ · 开源中国/Gitee Feedback](https://web.archive.org/web/20240506161836/https://gitee.com/oschina/git-osc/issues/I9L5FJ?from=project-issue)》, Gitee, 2024-05-01. (参照 2024-05-08).

> [!abstract]+ 相关讨论
>
> +   dong706, 《[Gitee Pages 已经失联第六天了...](https://web.archive.org/web/20240507075216/https://www.v2ex.com/t/1037924)》, V2EX, 2024-05-06. (参照 2024-05-08).
> +   laoxiong, 《[gitee.io 504 好几天了，是都没人管了吗？我用的一个 Markdown 工具还在上面呢-\_-](https://web.archive.org/web/20240507215014/https://v2ex.com/t/1038258)》, V2EX, 2024-05-07. (参照 2024-05-08).
> +   studyingss, 《[GiteePages 服务已下线](https://web.archive.org/web/20240507070551/https://www.v2ex.com/t/1038397)》, V2EX, 2024-05-07. (参照 2024-05-08).
