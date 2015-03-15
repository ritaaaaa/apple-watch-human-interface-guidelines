# 设计您的Apple Watch应用 - Designing for Apple Watch

> **重要提示**

>这是一篇关于 API 和相关发展技术的初步文档。苹果提供此文档便于你在苹果的产品上开发应用软件。此文档会根据情况做修改，所以根据此文档开发的软件应该在最终的操作系统上测试并符合最终的文档。新版的文档会进一步提供新版 API 以及相关技术支持。

![image](../images/HomeScreen_2x.png)

Apple Watch 体现出如下特性：

**人性化。**由于Apple Watch是可穿戴设备，它的用户界面（UI）要尽可能的简单、便于操作。使用者抬起手腕便可以看到时间和新消息。Digital Touch 提供了新型的交互方式。accelerometer 和心律传感器记录了使用者每天的活动信息。除了 Apple Watch ，没有任何一个苹果设备能如此贴近使用者。当你为 Apple Watch 设计 apps 时，请充分体现这个特征。

![image](../images/personal_digitaltouch_2x.png)

**整体性。** Apple Watch 模糊了软硬件的界线。The Digital Crown 是一个用于 app 中，给内容做精确导航的硬件设备。The Taptic Engine 为提醒和新消息提供了优质的样式。Force Touch ，创新了背景控制技术。尽管 Retina 屏幕的边缘导致了一些界面边界的设计失去效果。优质的 app 设计应该弱化软硬件的区别。

**轻量级。** Apple Watch 上的 app 要具有快捷、操作简单的特点，以便使用者能够在戴着 Apple Watch 的同时完成大多数的操作。为了隐私性和可用性，消息、提醒的出现和消除都应该是快速并且容易的。例如，短消息并不展示太多的信息除非使用者想查看更多，而这个查看操作要十分简单。你设计的app要尽量满足简洁、小巧、快捷的用户体验。

![image](../images/lightweight_weatherglance_2x.png)

WatchKit app 补充了 IOS app ，但并不是替代它。如果你与 IOS app 的交互时间是分钟级的，那么你与 WatchKit app 的交互时间就要到达秒级。所以交互的快捷和界面的简单十分重要。
