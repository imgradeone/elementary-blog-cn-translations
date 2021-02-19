---
title: 来聊聊 elementary OS 6
description: 7 月更新，以及下一个大版本的抢先体验
author: cassidyjames
image: https://blog.elementary.io/images/updates-for-july-2020/card.png
tags:
  - odin
  - updates
  - done-translation

---

不像其他操作系统（尤其是那些开源桌面界的操作系统），elementary OS 在每个大版本里都会频繁推出功能更新。这意味着在 elementary OS 5 的生命周期里，我们都会[每月发布更新](https://blog.elementary.io/tags/#updates)，包括系统修复，以及偶尔会发布的新功能，比如全新的首次启动体验，[全新的登录 / 锁屏界面](https://blog.elementary.io/say-hello-to-the-new-greeter/)，初始设置向导，及[欢迎向导](https://blog.elementary.io/get-settled-into-elementary-os-with-onboarding/)；与旁加载功能和应用中心配合的 [Flatpak 支持](https://blog.elementary.io/updates-for-october-2019/)；系统全局快捷键提示；[辅助功能设置更新](https://blog.elementary.io/accessibility-features-are-just-features/)；以及更多。与此同时，一系列为 elementary OS 开发的应用程序也在应用中心由开发者发布、更新。

半“滚动更新”的机制意味着，elementary OS 用户无需等待下一个大版本更新，就可以获得即时的最新功能、修复，以及他们最喜欢的系统及应用更新。然而，在整个生命周期里，我们需要在某个时间点将资源和优先事项转移到大版本上。大版本更新将带来更新的 Ubuntu 内核及仓库，以及背后的重大改进。而正如[上个月所讲](https://blog.elementary.io/updates-for-june-2020/)的那样，这个转移已经开始了。

## elementary OS 5.1 Hera 的更新

Hera 版本将继续收到来自 Canocial 的 Ubuntu LTS 底层库的安全及稳定性更新，到 2028 年 4 月结束。但我们 elementary 的眼光已经转移到了 OS 6。我们仍然会在 7 月和 8 月末之间针对 OS 5.1 发布一些更新：

在键盘设置里，我们已经添加了新的输入法视图。这将帮助 [Ibus](https://en.wikipedia.org/wiki/Intelligent_Input_Bus) 用户设置和管理输入法——而这个功能对输入中文、日文、韩文、越南文，以及其它字符的用户极其有用。

<figure markdown="1">

![系统设置 - 键盘里的新输入法设置视图](https://blog.elementary.io/images/updates-for-july-2020/input-method@2x.png)

<figcaption>系统设置 - 键盘里的新输入法设置视图</figcaption>
</figure>


我们也发布了针对顶栏音乐托盘图标的更新，在没有音乐播放的时候，您设置的默认音乐播放器（可在系统设置 → 应用程序 → 默认程序里修改）将会显示。这将让你更快地回到自己的音律当中，无论你喜欢哪个音乐播放器。

<figure class="card" markdown="1">

![显示其他音乐播放器的音乐托盘图标](https://blog.elementary.io/images/updates-for-july-2020/music-indicator@2x.png)

<figcaption>显示其他音乐播放器的音乐托盘图标</figcaption>
</figure>


应用中心的小型更新将保存并正确恢复窗口位置，同时点击顶栏的小数字徽标将可以直达更新页面。

感谢 Ubuntu 和 Canocial 的快速反应，elementary OS 5.1 Hera 已经通过更新正式修复了[“BootHole”漏洞](https://eclypsium.com/2020/07/29/theres-a-hole-in-the-boot/)。

您现在就可以通过应用中心，点击“更新全部”按钮获取这些更新，以及 bug 修复和翻译更新。新安装用户也可以下载 elementary OS 5.1.7 的更新镜像。

## AppCenter for Everyone

在 2 月，我们启动了 [AppCenter for Everyone](https://blog.elementary.io/appcenter-for-everyone/) 众筹项目，让这款独立开源的应用商店更上一层楼。我们几乎不知道这次席卷全球的 COVID-19 疫情会在我们计划进行面对面会议的时候来袭。我们完成了目标，但也只能推迟这么一次活动，而改为更小型的远程会议。我们远程完成了一些工作，但也没法完成所有 AppCenter for Everyone 的目标，毕竟我们仍然储备了一些资金，为了等到安全的时候举行一次真正的面对面会议。

其中一项参与者回馈是“elementary OS 6 的早期体验版”，这是我们转移目光后正在努力制作的。那么，接下来是……

## elementary OS 6 抢先体验版

在几周之前，我们悄然上线了 [builds.elementary.io](https://builds.elementary.io)。这个新网站托管着 elementary OS 的抢先体验版，以确保 OEM、开发者、测试人员、支持者和那些激动的粉丝能第一时间体验到最新的预发布版本。目前 elementary OS 6 已经达到了可安装、可启动的状态，我们也已经开始自动将那些在 AppCenter for Everyone 众筹项目中捐赠 25 美元及更多钱的人，以及所有在 GitHub Sponsors 中捐赠 10 美元/月 或更高档位的赞助者加入到抢先体验版名单中。如果你对新版本感到好奇，或者你现在就想体验抢先体验版，那么去访问下方的网站吧：

<div style="text-align: center">
  <p><a rel="nofollow noopener noreferrer" target="_blank" href="https://builds.elementary.io" class="button">elementary OS 抢先体验版版（英文）</a></p>
</div>

抢先体验版是您先人一步获得独家体验权、支持 elementary OS 长期发展，以及反馈早期功能的绝佳方式。仍然澄清一下，拥有定价及分发的正式版 elementary OS 将保持不变，最新的稳定版将仍然可以从 elementary.io 下载，依旧是随意出价。所有源代码完全开放，可以从 [GitHub](https://github.com/elementary) 获取。

### elementary OS 6 的新特性

现在我们已经有了抢先体验版，但是在 elementary OS 6 推出 beta 版之前，我们还有 *一大堆* 事情要做。这里就不列一排详情了，下面是一些仍在开发中的规划功能：

- **全新视觉体验**，包括字体以及系统设计样式——这将影响所有地方，从面板、系统应用，到应用中心里的应用。改进的对比度，重构的设计系统，同时保留 elementary OS 经典特色的深度与阴影。当然，还有一些小细节，比如应用窗口底部圆角边框，包括系统设置和终端。在此感谢 Libhandy’s HdyWindow。
  - **系统组件的暗黑模式**，比如 Dock、顶栏托盘图标、键盘快捷键提示窗口、系统提示框等。我们仍然在爆肝，但目前进展良好。
  - **用户自选的应用强调色**。应用程序如果自行选择了强调色，那么则会覆盖此设置；但此前的默认蓝莓色强调色，已经可以修改为一系列其他品牌色，包括草莓红、橙色、香蕉黄、青柠色、薄荷绿、葡萄紫，以及泡泡糖粉。
- **针对交流与组织应用的重大更新**，借助 Evolution 服务器后端。这仍旧处于早期阶段，在完成在线帐号系统之前，我们需要借助 Evolution 服务器。但在此感谢 Corentin Noël 对功能做出的巨大贡献。更新将启用支持一系列应用程序的邮件、日历事件、代办事项等的同步，并且支持许多帐号提供商。
  - **邮件软件大型重制**，基于 Evolution 数据服务器，替代原 Geary 邮箱引擎。视觉将保持一致，但现在还没到尽善尽美的程度。
  - **全新 Tasks（待办事项）应用程序**，本地待办事项及事项列表将同步到 Evolution 数据服务器。
- **全新安装器和初始设置向导**，革新首次启动体验。安装系统将比以前更快，流程也将更简单，只需要选择把系统安装到磁盘里需要的东西就行了。这对于 OEM 来说将更友好，他们现在可以直接用系统镜像，把系统装进设备里，或者（像我们就在玩的 Pinebook Pro 实验性镜像一样）把镜像刷进去，不新建用户，但允许用户在首次启动时直接开始初始设置向导。
- **更好的应用程序多指触控支持**，借助 Libhandy 库。手势适用于触摸屏、触摸板和鼠标滚轮。在触摸屏上，您的手指滑动手势将和触摸板一致。（？）Epiphany 也会支持手势操控返回 / 前进。
- **还有许多东西……** 现在咱只能分享这么多。😉

之后，随着开发进展，我们会分享更多 elementary OS 6 的更新内容，但现在，是时候揭开它的神秘面纱了。如果你想了解更多信息，你可以去看看 GitHub 上 [elementary OS 6 的项目面板](https://github.com/orgs/elementary/projects/55)，同时也欢迎大家[加入我们](https://elementary.io/get-involved)，一起塑造更好的未来。
