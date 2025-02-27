---
title: "Clash for Windows"
description:
published: true
date: "2024-11-09T00:23:32"
特殊标签标记: #无标签
editor: markdown
dateCreated: "2023-11-03T08:19:45"
---

## 简介

Clash for Windows 是 Fndroid 开发的 Windows、Linux 与 macOS 全桌面平台的 GUI，基于 Clash 核心和 Electron 框架。
（后文简称为 CFW）

不过 CFW 并没有开源，存在违反 GPL 的风险，好在 clash 的终身仁慈独裁者 Dreamacro，没有对此有异议。[^cl541]

[^cl541]: ghost, 《[Clash For Windows是否违反了Clash的GPL协议？ · Issue #541 · Dreamacro/clash](https://web.archive.org/web/20231025223859/https://github.com/Dreamacro/clash/issues/541)》, GitHub, 2020-02-27. (参照 2023-11-03).

## 删库

2023年11月2日 下午，CFW 的 GitHub 仓库，仅存放简介和软件的仓库 `https://github.com/Fndroid/clash_for_windows_pkg`，
被逐渐清空，最后整个仓库也被删除，63.2k stars 惊人数量的点赞也消失了。[^19349][^01751][^24923]

[^19349]: 李老师不是你老师, 「[刚刚，墙内最著名的翻墙软件Clash for windows 删库了](https://web.archive.org/web/20231102171940/https://nitter.net/whyyoutouzhele/status/1719989543837819349)」, X（Twitter）, 2023-11-02. (参照 2023-11-03).

[^01751]: 新时代草泥马, 《[【网络民议】知名翻墙客户端Clash for Windows删库停更](https://web.archive.org/web/20231102151730/https://chinadigitaltimes.net/chinese/701751.html)》, 中国数字时代, 2023-11-02. (参照 2023-11-03).

[^24923]: 8899, 《[家人们，出大事了](https://web.archive.org/web/20231103014048/https://hostloc.com/thread-1224923-1-1.html)》, 美国VPS综合讨论, 2023-11-02. (参照 2023-11-03).

Fndroid 随后在 Telegram 频道和 X（Twitter），发布了说明：「停止更新了，江湖再见吧😅」。[^09092]

[^09092]: Fndroid, 「[停止更新了，江湖再见吧😅](https://web.archive.org/web/20231102155205/https://nitter.net/fndroid/status/1719980029571109092)」, X（Twitter）, 2023-11-02. (参照 2023-11-03).

当天，CFW 的上游 Clash 暂时未受影响，其他使用了 Clash 核心的 GUI，比如 Clash verge、Clash for Android、ClashX、ClashN
也未受明显影响。

2023年11月3日，Clash 相关软件逐渐开始删库：

+   11-03 14:02 Dreamacro/clash（删）[^c_0]
+   11-03 14:10 MetaCubeX/Clash.Meta（存）[^c_1]
+   11-03 14:40 EAimTY/tuic（删）[^c_2]
+   11-03 14:40 Dreamacro/clash-dashboard（删）[^c_13]
+   11-03 14:44 lotusnetwork/lotusboard（存）[^c_16]
+   11-03 15:10 Z-Siqi/Clash-for-Windows_Chinese（存）[^c_15]
+   11-03 15:11 fw876/helloworld（删）[^c_3]
+   11-03 15:54 juewuy/ShellClash（更名为 ShellCrash，删）[^c_4]
+   11-03 16:02 Kr328/ClashForAndroid（删）[^c_5]
+   11-03 16:11 Clash Multiplatform（解散群组）[^c_6]
+   11-03 16:16 MetaCubeX/ClashMetaForAndroid（删、踢群员）[^c_7]
+   11-03 16:32 ModuleList/ClashF（存）[^c_8]
+   11-03 16:32 CHIZI-0618/box4magisk（存）[^c_8]
+   11-03 16:42 zzzgydi/clash-verge（存）[^c_9]
+   11-03 16:49 Fclash/Fclash（存）[^c_10]
+   11-03 16:50 immortalwrt/homebridger（存）[^c_11]
+   11-03 17:18 openrhc/GUI.for.Clash（删）[^c_12]
+   11-03 18:00 Fclash/Fclash（删）[^c_14]
+   11-03 18:42 mritd/tpclash（删）[^c_17]
+   11-03 19:57 yichengchen/clashX（删）[^c_18]
+   11-03 20:23 BoyceLig/Clash_Chinese_Patch（删）[^c_22]
+   11-03 22:12 AntiNeko/CatBoxForAndroid（存档）[^c_19]
+   11-04 12:27 missuo/XrayR-V2Board（删）[^c_21]
+   11-05 11:44 AntiNeko/CatBoxForAndroid（删）[^c_20]

[^c_0]: https://t.me/gledos_science/16545
[^c_1]: https://t.me/open_source_community/370986
[^c_2]: https://web.archive.org/web/20231103090655/https://hostloc.com/thread-1225733-1-1.html
[^c_13]: https://t.me/gledos_science/16617
[^c_16]: https://web.archive.org/web/20231103095724/https://github.com/lotusnetwork/lotusboard
[^c_15]: https://web.archive.org/web/20231103102751/https://github.com/Z-Siqi/Clash-for-Windows_Chinese/commits/main
[^c_3]: https://t.me/wtmsd/61789
[^c_6]: https://t.me/BDovo_Channel/2610
[^c_7]: https://t.me/BDovo_Channel/2613
[^c_8]: https://t.me/acgdaily/22989
[^c_9]: https://t.me/BDovo_Channel/2629
[^c_4]: https://t.me/BDovo_Channel/2602
[^c_5]: https://t.me/acgdaily/22984
[^c_10]: https://t.me/c/1731060325/9545
[^c_11]: https://t.me/c/1731060325/9547
[^c_12]: https://t.me/gledos_science/16584
[^c_14]: https://t.me/gledos_science/16615
[^c_17]: https://t.me/BDovo_Channel/2672
[^c_18]: 删除时间晚于 [16:19](https://web.archive.org/web/20231103120124/https://hostloc.com/thread-1225812-1-1.html)，19:57 检查时就被删除了。
[^c_19]: AntiNeko, [AntiNeko/CatBoxForAndroid](http://archive.today/2023.11.03-141256/https://github.com/AntiNeko/CatBoxForAndroid), GitHub, 2023-11-03. (参照 2023-11-05).
[^c_20]: https://t.me/open_source_community/371847
[^c_21]: Vincent Young, [missuo/XrayR-V2Board](https://web.archive.org/web/20231105081141/https://github.com/missuo/XrayR-V2Board/). 2023-11-05. 参照: 2023-11-05. [Online].
[^c_22]: https://t.me/EFW_inno/2223

括号中的（删）表示不再公开库，也包括创建空白分支，然后默认显示此空白分支，（存）表示存档仓库，意味着停止开发。

其中，TUIC 的作者编写了博文，阐述了删库的原因，大致是放下责任／卸下枷锁的时候到了，因为 Clash 删库成为了导火索，
最后表达了暂停开发的声明，并保留了恢复开发的可能性。[^opboh]

[^opboh]: EAimTY, 《[基于荷尔蒙开发的开源项目](https://web.archive.org/web/20231103102043/https://www.eaimty.com/2023/opensource-project-based-on-hormone/)》, EAimTY’s Blog, 2023-11-03. (参照 2023-11-04).

2023年12月2日，Telegram 上有人观察到 metacubex/Clash.Meta 复活了，[^hd]但修改了仓库名为 mihomo。[^97259][^85500]
而在文档里出现了这样的内容：「虚空终端是一个基于开源项目原神的二次开发版本」，有人认为是 meta → 元 → 原，
所以玩了原神的梗。[^22905]

[^hd]: 消息来源要求禁止转发。

[^97259]: icaolei, 《[开源的 Clash meta 内核复活了](https://www.v2ex.com/t/997259)》, V2EX, 2023-12-03. (参照 2024-11-08). 附言：存在登录墙。

[^85500]: 《[简介](https://web.archive.org/web/20241106085500/https://wiki.metacubex.one/)》, 虚空终端 Docs, 2024-02-08. (参照 2024-11-08).

[^22905]: 搞七捻三, 《[clash.meta内核_有趣的发现](https://linux.do/t/topic/122905)》, LINUX DO, 2024-06-28. (参照 2024-11-08).

## 流言

关于 Clash for Windows 删库的原因，有人猜测作者在推特分享了许多个人资料，比如汽车照片、网购截图等，暴露了自己。然后遭到 [有关部门](/censorship/有关部门.md) 施压，最终导致删库事件。[^01751][^70194]

[^01751]: 新时代草泥马, 《[【网络民议】知名翻墙客户端Clash for Windows删库停更](https://web.archive.org/web/20231225140104/https://chinadigitaltimes.net/chinese/701751.html)》, 中国数字时代, 2023-11-02. (参照 2024-03-02).

[^70194]: 学习墙国🐸, 「[建议大家别瞎截屏，注意保护个人信息！](https://web.archive.org/web/20240302082237/https://t.me/s/XueXi_China/70194)」, Telegram, 2023-11-02. (参照 2024-03-02).

不过无法确认具体删库原因，所以此消息真实性未知。
