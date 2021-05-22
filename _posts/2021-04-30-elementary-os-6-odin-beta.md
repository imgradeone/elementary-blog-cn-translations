---
title: elementary OS 6 Beta 现已发布
description: 啥是 Beta？能吃吗？对开发者又有什么用？
author: cassidyjames
image: https://blog.elementary.io/images/updates-for-july-2020/card.png
tags:
  - devs
  - early-access
  - odin
  - in-progress-translation
---

开发者和测试者们，让你们久等了。elementary OS 6 Beta 现已发布！去年 8 月，我们开始 [公开讨论 elementary OS 6](https://blog.elementary.io/updates-for-july-2020)。从此，我们也在一直处理庞大的工作范围，同时也在应对全球疫情的影响、旅行限制以及家人和朋友圈的损失。

尽管如此，我们还是为我们所做的工作感到由衷的自豪，并为在完成稳定版本的过程中能将新系统送到开发人员和测试人员手中测试而感到兴奋。

## 啥是 Beta？
进入正题之前，我们需要解释一下“Beta”到底是什么东西。elementary OS 的开发过程有三个节点：

- Early Access（抢先体验）
- Beta（公测）
- Release Candidate（候选发布）

Early Access 版本相当于“最前线”的版本，它使用每日更新的仓库（daily repo），即时更新发布，但没有像稳定版那种人工测试的过程。回到 2020 年 8 月，我们开始按照这种流程构建 elementary OS 6 的 Early Access 版。elementary 的赞助者都可以使用该版本，但我们不建议任何用户把 Early Access 装在日常使用的电脑中，因为早期的开发可能会引起频繁的、破坏性的问题。由于 Early Access 使用每日仓库，它将完全不可能直接升级到稳定版本。

Beta 版是 Early Access 的快照，在开发平台逐渐稳定下来后才会发布。到这个节点，我们邀请应用开发者开始在 elementary OS 上构建、测试应用。Beta 版同样使用每日仓库，因此我们也不建议将 Beta 版安装到日用机器，而且它一样不可以直接更新到稳定版。但是，一些东西会更加稳定 —— 尤其是直面开发者的 API 接口。**你现在就在这一阶。**

<aside>
<blockquote>
<p>Beta 版是 Early Access 的快照……我们也不建议将 Beta 版安装到日用机器</p>
</blockquote>
</aside>

Release Candidate，顾名思义：稳定版本的候选版本。RC 版本基于稳定仓库构建，也可以享受到严格的人工测试。到这一步，我们会认为这个版本是“完成版”，后续工作也就是在稳定版正式发布之前发现并修复剩余的 bug。

只要我们对最终 RC 版本的效果感到满意，它将被推送为稳定版本，

## 有什么新功能？
对于开发者来说，你们是幸运的，我们从去年 8 月就已经详解了 elementary OS 6 的诸多变化。作为起始点，你可以看看最早的 elementary OS 6 博文，这里我们注明了许多亮点：

<aside>
{% assign post = site.posts | where:"slug", "updates-for-july-2020" | first %}
{% include featured.html post=post %}
</aside>

但在这里，我们也整合了所有 elementary OS 6 的新特性，以及更加详细的、分化的博文链接。

## 平台变化
开发者需要注意 elementary OS 6 带来的 *一大堆* 新底层技术。新的 screen shield 支持在显示器睡眠后继续播放音频，为您的应用程序提供了新的使用案例。我们已经完全改造了通知系统，采用了全新的通知服务器和崭新的设计；请务必确认您的应用的通知能在 elementary OS 6 上正确显示，如果出现意外，也请及时反馈。

<aside>
{% assign post = site.posts | where:"slug", "platform-changes-in-elementary-os-6" | first %}
{% include featured.html post=post %}
</aside>

我们在 elementary OS 6 引入了 [LibHandy](https://valadoc.org/libhandy-1/Hdy.html)；我们鼓励开发者查看 elementary OS 6 的官方应用来了解如何使用这个库。尤其注意，将 Gtk.Stack 替换为 Hdy.Deck 会启用多指触控的导航手势，Hdy.Carousel 同样支持多指触控手势，但更适合翻页场景。Hdy.Avatars 会提供一些新头像，Hdy.Window 启用底部边框圆角，也有支持拖拽任意控件移动窗口的功能，同时 Handy 自身也包含一些布局，能让你的应用更能适应各种大小的屏幕。

<aside>
{% assign post = site.posts | where:"slug", "multitouch-gestures-in-elementary-os-6" | first %}
{% include featured.html post=post %}
</aside>
