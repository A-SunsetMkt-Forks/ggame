---
title: GitHub
description:
published: true
date: "2025-04-15T23:59:55"
tags:
- github
- gfw
editor: markdown
dateCreated: "2021-05-22T12:44:35"
---

## 简介

GitHub 是一个在线软件源代码托管服务平台，使用 Git 作为版本控制软件，在 2018 年被微软公司收购。

## GitHub 被拯救了两次

详情可以查看 Rei 在 2014年2月24日 编写的《[我们拯救了 Github 两次][sg2]》。

[sg2]: https://web.archive.org/web/20221207065318/https://chloerei.com/2014/02/24/we-saved-github-twice/

## App Store 大陆区下架

〔待续〕

> [!abstract]+ 相关链接
>
> +   [GitHub 正式上架 App Store 了 · Issue #1132 · ruanyf/weekly · GitHub](https://web.archive.org/web/20210522115601/https://github.com/ruanyf/weekly/issues/1132)
> +   [Github 官方 app 终于上架了 - V2EX](https://web.archive.org/web/20210522122657/https://www.v2ex.com/t/653739)
> +   [国区 App Store 里找不到 GitHub - V2EX](https://web.archive.org/web/20210522033157/https://www.v2ex.com/t/778475)

## Github Pages 受限

详情请阅读 [github.io](/website/次级域名/github.io.md) 条目，封锁发生在 2020年7月 月底。

## 网络劣化

2021年3月，有人发现 [GFW](/censorship/技术/GFW.md) 针对 GitHub 进行了网络劣化处理，原理是每隔一段时间，
随机封禁 GitHub 部分 IP 的 443 端口一段时间，即使刚才能正常访问，刷新一下就可能被主动封禁了。[^58568]

[^58568]: XIU2, 《[只要 Github 域名指向任意 IP，该 IP 的 443 端口就会超时 3 分钟（TCPing， 80 端口正常），求解！](https://web.archive.org/web/20230217100245/https://v2ex.com/t/758568)》, V2EX, 2021-03-04. (参照 2023-02-17).

## 广东封锁 Github

2022年5月27日，广东宽带用户发现 Github 在运营商 DNS 的情况下会被解析到 `127.0.0.1` 以及 `0.0.0.0`。[^855574][^4d24ec]

[^855574]: hhyygg, 《[运营商 DNS 将 GitHub 指向的本地](https://web.archive.org/web/20220528032521/https://www.v2ex.com/t/855574)》, V2EX, 2022-05-27. (参照 2022-05-28).

[^4d24ec]: 《[github.com DNS检测](https://web.archive.org/web/20220513014638/https://zijian.aliyun.com/detect/dns/DNS_PING-4d24ececaff9db99decd9d9d0b35203b-1652406274446)》, 阿里云网站运维检测平台. (参照 2022-05-28).

影响网站解析的运营商 DNS 至少有：

+   `202.96.128.86`
+   `202.96.134.33`

## 2022年12月 访问受限

2022年12月6日 左右，有人发现 GitHub 在大陆出现了大范围访问受限的情况。[^2ac5c][^900476][^900485] 比如使用 114 DNS，
会让 GitHub 跳转到反诈页面。[^dIL7A] 有人认为这与 GitHub 上面的 AntiZhaPian 仓库有关。[^900605]

[^2ac5c]: 《[检测目标https://github.com/](https://web.archive.org/web/20221206095415/https://boce.aliyun.com/detect/http/5d555ac9ce344acf8fa9c187b3a2ac5c)》, 阿里云网站运维检测平台, 2022-12-06. (参照 2022-12-08).

[^900476]: eightsheep, 《[github 访问的问题](https://web.archive.org/web/20221206095500/https://www.v2ex.com/t/900476)》, V2EX, 2022-12-06. (参照 2022-12-08).

[^900485]: w950888, 《[有人发现么, 今天电信访问 github 被解析到了国家反诈中心](https://web.archive.org/web/20221206095506/https://www.v2ex.com/t/900485)》, V2EX, 2022-12-06. (参照 2022-12-08).

[^dIL7A]: 🥥🐑 王小美 (@mashiro), 「[114.114.114.114会把GitHub劫持到到反诈中心页面](http://archive.today/2022.12.08-074530/https://m.moec.top/notes/98fey3rk7v)」, 萌c, 2022-12-08. (参照 2024-03-11).

[^900605]: zanzhz1101, 《[如何评价本次 github 被大范围 dns 污染](https://web.archive.org/web/20221206203742/https://www.v2ex.com/t/900605)》, V2EX／[水深火热](/website/V2EX.md#水深火热), 2022-12-06. (参照 2022-12-08).

## 2024 年大范围封锁

2024年1月16日，最早在凌晨的时候，就有用户发现 GitHub 难以连接，主要是难以通过 SSH 连接。[^13632][^05966][^09542][^agzif]

[^13632]: 「[https://github.com GFW 测试](http://archive.today/2024.01.19-015102/https://blocky.greatfire.org/detail/13632/https://github.com%23)」, Blocky, 2024-01-19. (参照 2024-01-19).

[^05966]: 「[www.17ce.com GET 测试结果](https://web.archive.org/web/20240118153340/https://17ce.com/site/http/20240118_ae9a0810b61611eebeeda57922605966:1.html)」, 网站速度测试 17CE, 2024-01-18. (参照 2024-01-19).

[^09542]: kylebing, 《[好奇怪，这两天 github 通过 ssh 的方式无法 push 或 pull 了](https://web.archive.org/web/20240119015312/https://v2ex.com/t/1009542)》, V2EX, 2024-01-18. (参照 2024-01-19).

[^agzif]: BG5USN, "[The ssh to GitHub is block by GFW today?](http://archive.today/2024.01.19-082013/https://twitter.com/BG5USN/status/1747288110197514262)", X (formerly Twitter), 2024-01-17. (参照 2024-01-19).

具体是 DNS 会被解析到 20.205.243.166，而这个 IP 被「空路由」，所以导致 GitHub 无法直连。[^09169]
所以使用 hosts 等方法就能解决。

[^09169]: zhanglintc, 《[你们的 GitHub 今天有问题吗？](https://web.archive.org/web/20240119015302/https://v2ex.com/t/1009169)》, V2EX, 2024-01-16. (参照 2024-01-19).

附言：影响范围尚不明确，还是有用户没有感到 GitHub 被封锁。

2024年2月19日，有人注意到了 GitHub 被解除封禁。具体来说，连通率高达 81.7 %
（<ruby>连通数量<rt>33</rt></ruby>／<ruby>全部节点<rt>180</rt></ruby>），[^7e381]
而之前的连通率受到 [网络劣化](#网络劣化) 影响，所以连通率在 50 % 左右。

[^7e381]: 「[www.17ce.com GET测试结果](https://web.archive.org/web/20240219070934/https://17ce.com/site/http/20240219_6c835600cef511ee8793ffe35d67e381:1.html)」, 网站速度测试 17CE, 2024-02-19. (参照 2024-02-19).

附言：2024年10月 的月初，GitHub SSH 再次被观察到封锁，范围是广州地区，[^77793] 暂未出现其他地区的封锁报告。

[^77793]: xuelang, 《[github ssh 协议也被封了？](https://web.archive.org/web/20241006092134/https://v2ex.com/t/1077793)》, V2EX, 2024-10-05. (参照 2024-12-04).

## 开源软件作者被跨省

2024年6月4日，Android 平台的多功能开源下载框架／库：Aria（与知名的 aria2 无关），其 GitHub 仓库代码也全部删除。[^60109][^60121]
可能是同一时间，Aria 作者 AriaLyy 的许多仓库也直接删除或隐藏了。[^01457][^62427][^04808]
其中有 KeepassA，这是 Android 平台的 Keepass 兼容客户端。[^52235]

[^60109]: AriaLyy, [Commits · AriaLyy/Aria](https://web.archive.org/web/20240817160109/https://github.com/AriaLyy/Aria/commit/b8236d1105d01462f66bf007482fe9b7ea84c5e1), GitHub, 2024-06-04. (参照 2024-08-17).
[^60121]: AriaLyy, [Commits · AriaLyy/Aria](https://web.archive.org/web/20240817160121/https://github.com/AriaLyy/Aria/commits/16e1fddca5996c1b2aba8b3284a0389f372ccf0b/), GitHub, 2024-06-04. (参照 2024-08-18).
[^01457]: AriaLyy, [AriaLyy/AbsAdapter: android Adapter 工具类](https://web.archive.org/web/20201011201457/https://github.com/AriaLyy/AbsAdapter), GitHub, 2020-10-11. (参照 2024-08-17).
[^62427]: AriaLyy, [AriaLyy/MVVM: Android MVVM框架](https://web.archive.org/web/20201209062427/https://github.com/AriaLyy/MVVM), GitHub, 2020-12-09. (参照 2024-08-17).
[^04808]: AriaLyy, [AriaLyy (lyy)](https://web.archive.org/web/20240327104808/https://github.com/AriaLyy), GitHub, 2024-03-27. (参照 2024-08-17).
[^52235]: AriaLyy, [AriaLyy/KeepassA: Android Keepass Software based on Keepass database](https://web.archive.org/web/20220924052235/https://github.com/arialyy/KeepassA), GitHub, 2022-09-24. (参照 2024-08-17).

2024年8月16日 10:32，因为有人在博文评论中咨询 Aria 的情况，然后作者回复：「因 Aria 被诈骗份子使用，导致我被跨省，
我不会维护也不会提供任何技术支持，建议自己解决。」[^62705]

[^62705]: AriaLyy, [Flutter实战-原来你是这样的Bloc - 水沝淼 · Issue #207 · AriaLyy/blog_comments](https://web.archive.org/web/20240817162705/https://github.com/AriaLyy/blog_comments/issues/207), GitHub, 2024-08-14. (参照 2024-08-18).

2024年8月16日 11:03，可能是为了防止再被打扰，作者更新了 Aria 仓库的 README.md（介绍），表示：「因 Aria 被诈骗份子使用，
导致我被跨省，因此本项目源码永久删除。最后说一句，诈骗份子死全家，奉劝给诈骗份子写代码的逼人和狗，别他妈用开源代码，
害了广大开源作者。」[^52110]

[^52110]: AriaLyy, [Update README.md · AriaLyy/Aria@eca89ea](https://web.archive.org/web/20240816052110/https://github.com/AriaLyy/Aria/commit/eca89ea8b64123a0702f4e293ea7a1c6f299f702), GitHub, 2024-08-16. (参照 2024-08-18).

2024年8月17日 09:09，IT 之家可能是最早报导此事的大体量媒体，[^25258] 之后新浪、凤凰网等媒体转载了 IT 之家 的报导，
但是消息源 IT 之家却在之后（早于 18 日）删除了报导，而转载的报导没有被删除。后续状况，有待观察。

[^25258]: 故渊, 《[开源下载器 Aria 因被诈骗分子使用，开发者清空 GitHub 代码库](https://web.archive.org/web/20240817025258/https://www.ithome.com/0/789/124.htm)》, IT之家, 2024-08-17 9:09:27. (参照 2024-08-18).

<!--

转载:
+   https://web.archive.org/web/20240817161607/https://finance.sina.com.cn/tech/digi/2024-08-17/doc-incixcsn5029380.shtml
+   https://web.archive.org/web/20240817161959/https://www.donews.com/news/detail/4/4485373.html
+   https://web.archive.org/web/20240819042045/https://tech.ifeng.com/c/8c7DKDkxzyc

其他:
+   https://web.archive.org/web/20240819042057/https://www.oschina.net/news/307530

-->

附言：有件类似的事件，是在 2021 年，有人开发了一键封装网页为 Android/iOS App 的软件。
但是被欺诈师用来制作诈骗 App，警方根据 App 签名找到了开发者，最终判处缓刑。期间开发者的未婚妻走了，工作丢了……

> [!note]+ 开发者 kosuo 的故事
>
> 2021年6月，开发者 Kosuo 在 Hostloc（全球主机交流论坛）上表示，他开发并免费分享的网页封装为 App 的软件，已被诈骗者滥用，
> 用于制作诈骗 App。由于软件的签名是 Kosuo 的，因而被抓进了看守所。[^59851]
>
> Kosuo 表示因为严打，每个警局都有抓捕诈骗的指标。所以杭州、温州、福建、北京、上海和南京的警察都来见 Kosuo。
> Kosuo 先在杭州被关进看守所 37 天，之后检察院认为证据不足而不批准逮捕，Kosuo 办理取保候审后才获得了自由。[^59851][^59229]
> 而在被关入看守所期间，Kosuo 失去了未婚妻、工作，还上了征信黑名单。[^59851]
>
> 之后从福建来了 8 个刑警，从阳台窗户翻入 Kosuo 的住所，按住后带走审讯。不过这还不是最糟糕的，更糟的是，
> 当着邻居和新同事的面，直接带走。当然也有好点的，那就是打电话要求协助调查。[^59851]
>
> 2021年10月，Kosuo 的案子终于宣判，被以「非法获取计算机信息系统数据罪」判处有期徒刑六个月，缓刑一年。罚金 1 万，
> 退回赃款 1.5 万。[^02891] 之所以有「赃款」，是因为 Kosuo 将软件源码卖给了别人。（不过警方没能找到买家）
>
> > [!rule]+ 判决书摘录[^02891]
> >
> > 第六十四条的规定，判决如下：
> >
> > 一、被告人**许金星**{: .mohu }犯非法获取计算机信息系统数据罪，判处
> > 有期徒刑六个月，缓刑一年，罚金人民币一万元。
> >
> > （缓刑考验期限从判决确定之日起计算。罚金已缴纳。）
> >
> > 二、退赃款人民币 15000 元，由公安机关发还被害单位。
> >
> > 如不服本判决，可在接到判决书的第二日起十日内，通过本
> > 院或者直接向江苏省南京市中级人民法院提出上诉。书面上诉的，
> > 应当提交上诉状正本一份，副本二份。
> >
> > 审判员：**洪超兰**{: .mohu }
> > {: align=right }
>
> 宣判后，Kosuo 需要去开通手机定位，将位置信息交给司法局社区矫正管理局，并参加社区劳动。即便如此，还是不断有警方传唤，
> 每次都要解释情况。[^04585] 并且因为开不了无犯罪记录证明，所以做不了很多工作（比如跑外卖）。
>
> 这让 Kosuo 到 Hostloc 发布求助帖子，请求外包业务给他。[^13709] 然而还是因为不断有各地的警方传唤，
> 至少导致了两次交付延期。[^42753][^13761] 他最后在 2023年3月30日 停止登录 Hostloc，后续情况不明。[^53173]
>
> <!-- 「去年 12 月的时候也是一个 mjj 找我做东西，给了 1k，回头我就给湖州薅走了。等我回来那哥们都把我删了已经。」 -->
>
> 然而 Kosuo 被数人指责收了钱，却不做事，或极度拖延。其中有两个质疑 Kosuo 的帖子，表示 Kosuo 拖延了半年和一年半工作，[^40413][^53173]
> 不主动联系等情况。圈钱后跑路，这是 Kosuo 被认为消失的原因。然而具体的消失原因，可能永远也无法知晓了。

<!-- 现在还好，跟网安合作搞点事 -->

[^59229]: kosuo, 《[没事不要做非法的事，还有12天就判了，忐忑](https://web.archive.org/web/20210620001655/https://hostloc.com/thread-859229-1-1.html)》, 全球主机交流论坛, 2021-06-20. (参照 2024-08-18).

[^59851]: kosuo, 《[今天福建刑J来了，又差点被带走](https://web.archive.org/web/20210621172018/https://hostloc.com/thread-859851-1-1.html)》, 全球主机交流论坛, 2021-06-22. (参照 2024-08-18).

[^02891]: kosuo, 《[一切终于尘埃落定，判六个月缓一年，罚金若干](https://web.archive.org/web/20211012004022/https://hostloc.com/thread-902891-1-1.html)》, 全球主机交流论坛, 2021-10-11. (参照 2024-08-18).

[^04585]: kosuo, 《[判缓刑后续，又被湖州警方找了](https://web.archive.org/web/20211015095601/https://hostloc.com/thread-904585-1-1.html)》, 全球主机交流论坛, 2021-10-15. (参照 2024-08-18).

[^13709]: kosuo, 《[来点业务啊，缓刑期天天要打卡检查，公司也不让开](https://web.archive.org/web/20211128043525/https://hostloc.com/thread-913709-1-1.html)》, 全球主机交流论坛, 2021-11-04. (参照 2024-08-18).

[^42753]: kosuo, 《[缓刑又尼玛被传讯了，风里雨里，你奶。。。](https://web.archive.org/web/20220825231602/https://hostloc.com/thread-942753-1-1.html)》, 全球主机交流论坛, 2021-12-20. (参照 2024-08-18).

[^13761]: kosuo, 《[定制那个，我不是骗子哈，不过确实是我耽误这个哥们事了](https://web.archive.org/web/20240818142616/https://hostloc.com/thread-1013761-1-1.html)》, 全球主机交流论坛, 2022-05-08. (参照 2024-08-18).

[^40413]: mfyidc, 《[我太相信MJJ了被骗10天完成的工作,托了半年还没交付](https://web.archive.org/web/20240818143411/https://hostloc.com/thread-1040413-1-1.html)》, 全球主机交流论坛, 2022-07-01. (参照 2024-08-18).

[^53173]: 豌豆荚, 《[kosuo大佬 你能把钱还了吗？活不干，qq删除，站内消息不回](https://web.archive.org/web/20240818135416/https://hostloc.com/thread-1153173-1-1.html)》, 全球主机交流论坛, 2023-03-29. (参照 2024-08-18).

## 网络测试

| 时间               | 测试工具 | 节点数量 | 连通数量 | 连通率 |
| ------------------ | -------- | -------- | -------- | -----: |
| 2024-01-18[^05966] | 17CE     | 176      | 13       |  7.4 % |
| 2024-02-19[^7e381] | 17CE     | 180      | 147      | 81.7 % |
| 2024-02-21[^qD5xo] | 阿里云   | 238      | 193      | 81.1 % |
| 2024-02-22[^odcrM] | 阿里云   | 236      | 193      | 81.8 % |

[^qD5xo]: [github.com HTTP Test](https://ghostarchive.org/archive/qD5xo "https://boce.aliyun.com/detect/http/4c020e9f7f0f4f56ab2686f90a5987d1"), 阿里云网站运维检测平台, 2024-02-21. (参照 2024-02-22).

[^odcrM]: [github.com HTTP Test](https://web.archive.org/web/20240222031149/https://boce.aliyun.com/detect/http/c266725cc83e48488dedea180cab3873), 阿里云网站运维检测平台, 2024-02-22.

## 大陆无法连接的一天

2025年4月13日 上午，大陆 IP 访问 GitHub 且未登录时，高概率会出现「Access to this site has been restricted」提示，
也就是访问受限的意思。[^25154][^82752]

[^25154]: [Access to this site has been restricted · community · Discussion #156515](https://github.com/orgs/community/discussions/156515), GitHub, 2025-04-13. ([Internet Archive](https://web.archive.org/web/20250413135923/https://v2ex.com/t/1125154), 参照 2025-04-15).

[^82752]: github.com GET 测试结果, 17CE, 2025-04-13. ([Internet Archive](https://web.archive.org/web/20250413050541/https://www.17ce.com/site/http/20250413_0a9bd740182411f0b3e2f1f3d5982752:1.html), 参照 2025-04-15).

搜索「Access to this site has been restricted」之后，会发现未登录的情况下，对 GitHub 的请求过多也会出现，
属于防滥用功能。[^stoh4] 考虑到 2015 年，GFW 对 GitHub 进行了 5 天的持续攻击（[大炮][]），所以现在又出现了网络攻击，
亦或是 GitHub 的防滥用功能出错了？

[^stoh4]: BrockPlaysFortniteYT, [Access to github denied?](https://www.reddit.com/r/AskProgramming/comments/12stoh4/access_to_github_denied/), r/AskProgramming, 2023-04-20. (参照 2025-04-15).

[大炮]: https://zh.wikipedia.org/zh-tw/大炮_(网络攻击工具)

关于「源代码禁运」的可能性，有伊朗用户分享了篇文章。[^2cb74] 其中详细描述了被封禁的过程，首先是收到邮件信息，
告知帐号被限制。然后虽然能够正常打开 GitHub 网页，但访问自己的私有仓库时，会显示「This repository has been disabled」，
并在个人主页上挂出横幅，表示该帐号由于美国贸易管制法而被限制。

[^2cb74]: Hamed, [GitHub blocked my account and they think I’m developing nuclear weapons](https://medium.com/@hamed/github-blocked-my-account-and-they-think-im-developing-nuclear-weapons-e7e1fe62cb74), Medium, 2020-10-11. ([Internet Archive](https://web.archive.org/web/20190725170128/https://medium.com/@hamed/github-blocked-my-account-and-they-think-im-developing-nuclear-weapons-e7e1fe62cb74), 参照 2025-04-15).

虽然不排除未来出现「源代码禁运」的可能，但目前的情况来看，最大的可能，还是 GitHub 的防滥用功能被触发了吧。
至于是故障还是遭到「大炮」攻击，还需要看 GitHub 的回应。

2025年4月13日 晚间，GitHub 修复了故障，稍后发布了错误报告，原因是「配置更改造成了意外影响」。
后续似乎还更新了处理问题速度过慢的原因「在此期间，来自中国的所有匿名请求中，高达 4 % 未成功。」[^9swln]

[^9swln]: [[Retroactive] Access from China temporarily blocked for users that were not logged in](https://www.githubstatus.com/incidents/jfvgcls9swln), Incident Report for GitHub, 2025-04-13. ([Internet Archive](https://web.archive.org/web/20250415151051/https://www.githubstatus.com/incidents/jfvgcls9swln), 参照 2025-04-15).

2025年4月15日，GitHub 又出现故障，将 Safari 浏览器给拦截了，好在不到一小时就解决了该问题。[^bghdy]

[^bghdy]: [Disruption with some GitHub services for Safari Users](https://www.githubstatus.com/incidents/0r3t35cbghdy), GitHub, 2025-04-15. ([Internet Archive](https://web.archive.org/web/20250415145733/https://www.githubstatus.com/incidents/0r3t35cbghdy), 参照 2025-04-15).
