---
title: elementary OS 6 Odin 现已正式发布
description: 最大的平台更新，如今终于到来
author: cassidyjames
image: https://blog.elementary.io/images/elementary-os-6-odin-released/odin.png

tags:
  - flatpak
  - odin
  - release
  - in-progress-translation
---

<figure class="card" markdown="1">

![elementary OS 6 Odin](https://blog.elementary.io/images/elementary-os-6-odin-released/odin.png)

</figure>

elementary OS 6 的开发之路很漫长 —— 尤其是全球疫情影响中途开发，但今天它终于发布了。elementary OS 6 Odin 现已开放下载。这一次也是针对平台的最大更新！在 OS 6 中，我们专注于：

- 让你**充分掌控、表达自我**，
- 借助**新功能**不断开拓创新，以及
- 让 elementary OS **更易获取**、**更加包容**

如果您想立刻获取 elementary OS 6，那么可以前往 [elementary.io](https://elementary.io/) 下载 —— 或者先阅读本次更新内容的概览。

## 充分掌控，表达自我

elementary OS 的设计初衷是易于使用、不妨碍用户，将困难留给自己，将简便留给您。同时，这也让你可以轻松控制自己的设备和数据，因此我们才会留下这些宏大的 [隐私承诺](https://elementary.io/privacy)：

<aside>
<blockquote>
<p>
你的数据永远只属于你自己，我们不会做所谓的“广告个性化”或收集你的隐私数据。我们的经费直接来源于用户购买，包括自愿付费的 elementary OS 和应用中心内的应用程序。这才是开源应有的样子。
</p>
</blockquote>
</aside>

在 OS 6，我们借新的体验控制方式为您赋能 —— 外加充分表达自我风格和喜好的全新功能。

### 暗色主题 + 强调色

准备好关灯了吗？elementary OS 6 暗黑模式已经准备就绪。全新的暗色主题已经在欢迎窗口，以及 *系统设置* → *桌面* → *外观* 随时就命。选择传统的默认主题或者暗色主题时，系统及默认应用会自动适应更改。我们也鼓励第三方应用适应这一新特性，但为了避免打断开发进程，我们不会 *强制* 要求开发者适配；如果你喜欢的软件没有适配这一特性，请一定要向软件开发者反馈。暗色模式也可以根据所在地区日出 / 日落时间，以及你自己的时间表来自动切换。

<figure class="half" markdown="1">

![欢迎页](https://blog.elementary.io/images/elementary-os-6-odin-released/onboarding.png)
![桌面外观设置](https://blog.elementary.io/images/elementary-os-6-odin-released/appearance.png)

<figcaption><strong>左：</strong>欢迎页的暗色主题及强调色选项 | <strong>右：</strong><i>系统设置</i> → <i>桌面</i> → <i>外观</i></figcaption>
</figure>

我们也在 elementary OS 增加了 10 种新的强调色，它影响系统全局，从建议操作的按钮、开关，到文本选择焦点 —— 外加全新的基于桌面壁纸自动选择强调色的功能。elementary OS 6 是有史以来可定制程度最高的版本，它赋予您通过修改壁纸、视觉风格、强调色来彻底更改系统视觉的权力。

<aside>
<blockquote>
<p>elementary OS 6 是有史以来可定制程度最高的版本，它赋予您......彻底更改系统视觉的权力。
</p>
</blockquote>
</aside>

这些新功能的诞生离不开完全重写、重新设计的 elementary OS 系统样式表。我们重新审视了每一处细节，从上下文遮蔽、对比度，到阴影、边框和圆角半径，由此确保整个系统的对比度 *更加* 合适，同时也实现了前所未有的高度定制。

### 沙盒 + Portal

elementary OS 6 采用了前沿的沙盒技术，实现技术层面上的隐私和安全保护。在 OS 6，应用中心的应用将采用 Flatpak 打包、分发。Flatpak 是一种现代容器格式，它可以将应用程序与其它一切数据隔离开来 —— 包括您的敏感数据。elementary OS 的一些预装应用现在也采用 Flatpak 分发。

此外，elementary OS 6 借助 Portal 来控制应用间的交互方式以及您的数据。应用必须明确请求许可，且必须表明用途，例如访问文件，或者启动其他应用程序。全新的权限管理页面已经在 *系统设置* → *应用程序* 上线，您可以在此查看应用所请求的权限，也可以在此撤销授权。

<figure markdown="1">

![应用程序权限设置](https://blog.elementary.io/images/elementary-os-6-odin-released/permissions.png)

<figcaption><i>系统设置</i> → <i>应用程序</i> → <i>权限</i></figcaption>
</figure>

这些保护措施适用于从应用中心获取的应用，但更重要的是，它也适用于通过内置的旁加载（Sideload）工具安装的应用 —— 包括所有第三方 Flatpak 外部来源，如 Flathub 和开发者的个人网站。得益于这些内置保护措施，以及 elementary OS 6 的 Flatpak 优先原则，您现在可以更简便、更安全地获取并使用你想要的应用。

## 新功能

没有提升体验的新功能就没有新的大版本更新，elementary OS 6 就提供了许多新功能。

### 多点触控

对于触屏和触控板用户最为重要的功能之一，就是 elementary OS 6 系统全局支持多点触控。三指向上滑动可以流畅打开多任务视图，展示已打开的应用和工作区。三指左右滑动可以在动态工作区间平滑切换，来回跳转更加快速。

<figure class="half card" markdown="1">

![多任务视图](https://blog.elementary.io/images/multitouch-gestures-in-elementary-os-6/multitasking.gif)
![切换工作区](https://blog.elementary.io/images/multitouch-gestures-in-elementary-os-6/workspaces.gif)

<figcaption>
  <p>1:1 触控手势，用于多任务视图和切换工作区</p>
</figcaption>
</figure>

但这不仅仅是桌面的多点触控支持；我们也将丝滑直观的双指手势带入了应用中。您可以在翻页布局中双指滑动，像应用中心的屏幕截图、日期和时间托盘图标的月份页，以及初始设置和欢迎页的步骤。双指滑动即可在桌面和通知中心忽略通知。滑动即可返回 Web、系统设置和其他应用。你也可以在登录 / 锁屏界面滑动切换用户。

<figure class="third" markdown="1">

![应用中心截图](https://blog.elementary.io/images/multitouch-gestures-in-elementary-os-6/appcenter.gif)
![通知中心](https://blog.elementary.io/images/multitouch-gestures-in-elementary-os-6/notification-center.gif)
![键盘布局](https://blog.elementary.io/images/multitouch-gestures-in-elementary-os-6/keyboard-layouts.gif)
<figcaption>
  <p><strong>左：</strong>滑动切换页面 | <strong>中：</strong>滑动忽略通知 | <strong>右：</strong>滑动以返回</p>
</figcaption>
</figure>

这些全新的多点触控手势让 elementary OS 6 在触屏和触控板环境下的交互更加快速、流畅 —— 而这些交互就和传统的键鼠交互一样简便。多点触控手势可以在 *系统设置* → *鼠标和触控* → *手势控制* 中自定义。 

### 通知

elementary OS 一直提供桌面通知，但 OS 6 将通知重写底层、重新设计，让通知更加丰富、全能。

<figure class="half">
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-beta-2/notification-badge.png" alt="带图标的通知" width="362" height="90" tabindex="-1">
<img src="https://blog.elementary.io/images/elementary-os-6-odin-beta-2/notification-button.png" alt="带操作按钮的通知" width="362" height="129" tabindex="-1"></p>
  <figcaption>
    <p>全新通知气泡</p>
  </figcaption>
</figure>

通知气泡现在支持徽章 / 图标功能，让应用能发送类似角标的更丰富的信息，同时您也可以知道通知来自哪个应用。应用程序现在也可以同时发送带操作按钮的通知，按钮将展示在通知气泡中 —— 不需打开应用即可快速执行操作，这是从未有过的简便。

<figure>
  <picture>
    <source srcset="https://blog.elementary.io/images/elementary-os-6-odin-released/notification-dark.png" media="(prefers-color-scheme: dark)">
    <img alt="Urgent notification bubble" src="https://blog.elementary.io/images/elementary-os-6-odin-released/notification-light.png" width="362" height="90" tabindex="-1">
  </picture>
<figcaption>紧急通知的气泡</figcaption>
</figure>

由于通知现在和原生应用一样，使用原生 GTK 控件，通知气泡现在也跟随暗色风格，同时也支持全彩 emoji。紧急通知采用了新的外观和特殊的音效，使其更容易识别。最后，通知气泡也支持触摸屏和触控板的滑动忽略手势。

<figure class="card">
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/notification-center.png" alt="通知中心" width="750" height="497" tabindex="-1"></p>
  <figcaption>
    <p>重新设计的通知中心</p>
  </figcaption>
</figure>

通知中心也同样经过了重新设计，这里的通知与气泡的视觉一致，包括全彩 emoji 和图标，同时根据应用分类，也支持滑动忽略。

### 待办事项
全新的待办事项应用现已内置于 elementary OS 6，它将帮助您处理您的待办事项清单，无论数据存储于本地或是借助在线账号同步。

<figure markdown="1">

![待办事项](https://blog.elementary.io/images/elementary-os-6-odin-released/tasks.png)

</figure>

待办事项借助开源的 CalDav 格式，确保数据兼容大部分在线账号服务。它支持与多个账户和列表同步，支持基于时间、位置的提醒，以及更多。

### 固件更新

elementary OS 6 内置了由 [Linux Vendor Firmware Service](https://fwupd.org) 支持的固件更新功能。固件更新将向硬件厂商兼容的设备提供，包括 Star Labs、Dell、Lenovo、HP、Intel、Logitech、Wacom、8bitdo 等厂商都已支持 —— 现在，支持的设备都可以在 *系统设置* → *系统信息* → *固件* 中，或者在应用程序菜单搜索“固件”（Firmware）获取更新。

<figure class="constrained">
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/firmware.png" alt="固件设置" width="892" height="659" tabindex="-1"></p>
  <figcaption>
    <p>系统设置内置的固件更新</p>
  </figcaption>
</figure>

## 应用更新

elementary OS 6 的一些应用拥有了全新功能，得益于此，OS 6 才更加全能。

<figure class="half">
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/web.png" alt="Web in a light style" tabindex="-1">
<img src="https://blog.elementary.io/images/elementary-os-6-odin-released/web-dark.png" alt="Web in a dark style" tabindex="-1"></p>
  <figcaption>
    <p>在亮色和暗色模式下的 Web 浏览器</p>
  </figcaption>
</figure>

elementary OS 6 的内置网页浏览器已经更新、更名。此前被人们称为“Epiphany”的 Web 浏览器已经采用 Flatpak 打包，将带来更迅捷的更新，让 Web 浏览器支持最前沿的网络技术。Web 浏览器也提供了智能跟踪防护和内置广告拦截，这些选项默认启用，为您提供开箱即用的更佳隐私防护。新的阅读模式为内容繁杂的页面带来了简化的、更易阅读的视图。Web 浏览器跟随新的暗色风设置，同时应用于浏览器自身 UI，以及支持标准化 CSS 色彩方案（color scheme）设置的网站。同时，前面也有所提及的是，Web 浏览器也支持触摸屏和触控板的滑动返回 / 前进。

<figure>
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/mail.png" alt="邮件" width="1352" height="777" tabindex="-1"></p>
  <figcaption>邮件</figcaption>
</figure>

邮件应用在 OS 6 中已经过完全重写。随着软件重写，由 Evolution 数据服务器提供的在线账号集成也更为紧密。作为起始点，全新的系统全局在线账号设置支持 IMAP 标准的邮件账号，但我们可以在未来提供更多账号类型。这次重写同时也带来了网页进程沙盒化，每个邮件都在各自的沙盒中显示，大幅提高了安全性。全新的邮件应用在消息列表和对话视图中使用原生控件设计，而不是自定义组件，大幅增强了 RTL（从右至左）语言的兼容性以及全平台无障碍功能的支持。

<figure>
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/calendar.png" alt="日历" width="1039" height="765" tabindex="-1"></p>
  <figcaption>日历</figcaption>
</figure>

日历应用同样支持在线账号集成，但借助 CalDav 标准；现在前往系统设置添加支持 CalDaav 的账号，之后日历事件和待办事项都会展现在各自的应用中。我们也添加了 ICS 事件文件导入，优化了离线支持，修复了有关全天事件和时区的大量问题。

<figure>
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/camera.png" alt="相机" width="704" height="544" tabindex="-1"></p>
  <figcaption>相机</figcaption>
</figure>

在 OS 6 中，我们改进了相机应用，带来新 UI 和新功能。相机应用现已支持切换多相机，设置镜像图片开关，以及亮度、对比度修改。结束视频录制后，相机应用会在内部自动发送带有打开视频按钮的通知，让你更快确保视频和你所想的一致。

<figure>
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/appcenter.png" alt="应用中心" width="1081" height="669" tabindex="-1"></p>
  <figcaption>应用中心</figcaption>
</figure>

由于 elementary OS 6 已全局采用 Flatpak，应用中心也已经适配这一标准。我们一直在审核应用中心的第三方应用，但这一次，这些应用也已经采用沙盒化的 Flatpak 来分发，大幅增强了隐私和安全性。应用安装完成后，应用中心会自动弹出一条通知，让您更快速地打开应用。我们改进了应用标题栏的设计，包括按钮的对比度。应用中心的通知现在提供了更丰富的内容，为已安装的应用程序和更新提供了改进的文本与图标标志。

<figure>
  <p><img src="https://blog.elementary.io/images/elementary-os-6-odin-released/files.png" alt="文件" width="924" height="608" tabindex="-1"></p>
  <figcaption>文件</figcaption>
</figure>



---

## 注意！
本文目前暂时没有翻译完成，但不必慌张，您可以点击页面顶部的 [阅读英文原文](https://blog.elementary.io{{ page.url }}) 来继续阅读，或者点击下方的按钮：

<div style="text-align: center">
  <p><a rel="nofollow noopener noreferrer" target="_blank" href="https://blog.elementary.io{{ page.url }}" class="button">阅读英文原文</a></p>
</div>
