---
title: GitHub
description:
published: true
date: "2024-08-18T01:07:43"
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

[^25258]: 故渊, 《[开源下载器 Aria 因被诈骗分子使用，开发者清空 GitHub 代码库](https://web.archive.org/web/20240817025258/https://www.ithome.com/0/789/124.htm)》, IT之家, 9:09:27-. (参照 2024-08-18).

附言：有件类似的事件，是在 2021 年，有人开发了一键封装网页为 iOS App 的，免越狱免签名软件。
但是被欺诈师用来制作诈骗 App 了，警方根据 App 签名找到了开发者，最终判处缓刑。期间开发者的未婚妻走了，工作丢了……

<!--

转载:
+   https://web.archive.org/web/20240817161607/https://finance.sina.com.cn/tech/digi/2024-08-17/doc-incixcsn5029380.shtml
+   https://web.archive.org/web/20240817161959/https://www.donews.com/news/detail/4/4485373.html

其他:
+   https://www.oschina.net/news/307530

-->

## 网络测试

| 时间               | 测试工具 | 节点数量 | 连通数量 | 连通率 |
| ------------------ | -------- | -------- | -------- | -----: |
| 2024-01-18[^05966] | 17CE     | 176      | 13       |  7.4 % |
| 2024-02-19[^7e381] | 17CE     | 180      | 147      | 81.7 % |
| 2024-02-21[^qD5xo] | 阿里云   | 238      | 193      | 81.1 % |
| 2024-02-22[^odcrM] | 阿里云   | 236      | 193      | 81.8 % |

[^qD5xo]: [github.com HTTP Test](https://ghostarchive.org/archive/qD5xo "https://boce.aliyun.com/detect/http/4c020e9f7f0f4f56ab2686f90a5987d1"), 阿里云网站运维检测平台, 2024-02-21. (参照 2024-02-22).

[^odcrM]: [github.com HTTP Test](https://web.archive.org/web/20240222031149/https://boce.aliyun.com/detect/http/c266725cc83e48488dedea180cab3873), 阿里云网站运维检测平台, 2024-02-22.
