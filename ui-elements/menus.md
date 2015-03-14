# 菜单 - Menus

在 Apple Watch 的 Retina 屏上使用 Force Touch 手势能够触发当前屏幕的情景菜单，在不占用界面空间的同时，菜单中存储了与当前屏幕相关的 Action。

！[image](../images/menu_stopwatch_2x.png)

* 菜单展示了 1 到 4 项适用于当前屏幕相关的操作。
* 菜单中所展示的操作按照添加的顺序从上至下、从左向右排列。
* 菜单不能分层，也不能滚动。
* 菜单可以在设计阶段配置，或是以编程的形式进行配置。

**只有当前屏幕上包含相关 Action 时，才可以使用菜单。**菜单是可选择的。如果当前屏幕没有提供菜单，当用户在显示屏上使用 Force Touch 手势时，系统会展示一个相应的动画。

**不要创建一个仅适用于当前界面所选中的项目的，或是仅作用于界面一部分的 Action 。** Action 应当适用于整个屏幕。

**每个 Action 必须有一个图片和一个标签字符串。**用作菜单的图片必须是应用于标准背景的系统样式。标签字符串应尽可能简短，并且限定在 2 行以内。请记住，图片和字符串都是必须的。

关于创建菜单中图标的内容，请参看： [Menu Images](https://developer.apple.com/library/prerelease/ios/documentation/UserExperience/Conceptual/WatchHumanInterfaceGuidelines/MenuImages.html#//apple_ref/doc/uid/TP40014992-CH18-SW1)


