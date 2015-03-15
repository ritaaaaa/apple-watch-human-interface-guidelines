#通知-Notifications#
Apple Watch 的通知功能为本地和远程通知提供了更为快捷，轻量级的交互，这种交互呈现为两种——短界面（Short-Look）和长界面（Long-Look）。当本地或者远程通知首次到达时,展示短界面，该界面为穿戴者显示了精密设计过的的最少量信息，从而实现一定程度上的隐私保护。如果穿戴者压低手腕，短界面会消失；如果穿戴者抬高手腕或者点击短界面，则会显示长界面。长界面可以显示更多详细信息和功能，并且长界面必须只能被穿戴者有效解除。<br/>
**谨慎选择向用户发送通知的频率。**  &nbsp;用户可能会将频繁推送的信息看做骚扰信息，并禁用你的应用程序在Apple Watch上的通知功能，所以确保通知内容与用户需求总是相关。
##短通知界面（Short-Look Notifications）##
短界面可以让用户知晓哪款应用程序收到了通知，并只作简略展示。短界面是基于模板的，包含app的名称、标志以及通知标题。系统使用app的主色展示app的名称。<br/>
![shortlook_calendar_2x](../images/shortlook_calendar_2x.png)<br/>
**保持标题简短，重点突出。** &nbsp;屏幕上留给标题的可用空间很小，所以要尽可能的保证标题简洁、直切要点。标题并不提供通知的细节，只提供一个简短的提示。<br/>
##自定义长通知界面（Custom Long-Look Notifications）##
长界面提供了到达通知的更多细节。系统提供了默认的长界面外观，但你可以自行定义包含自己的图形和品牌的自定义长界面。长界面对所有app使用一样的结构，在界面顶部，系统提供了用以展示app 标志和app名称的肩形标题栏（sash），界面底部是一个解除按钮，中间是你的自定义内容和任意app专有的动作按钮。<br/>
![longlook_calendar_2x](../images/longlook_calendar_2x.png)<br/>
**提供静态界面（static interface ）并恰当的提供动态界面（dynamic interface）。**&nbsp;  动态界面比静态界面更具配置性，但两者都能用你的自定义图形和品牌展示相同的通知类型。另外，当动态界面不可用时，静态界面提供了退路。<br/>
**最多显示4个自定义操作按钮 （custom action button）。** &nbsp; Apple Watch利用被你的iOS app认证过的交互式通知在长界面展示操作按钮。自定义操作按钮会根据通知的类型自动展开，除此之外还会显示系统提供的解除按钮。<br/>
**设置与你的品牌相配的肩形标题栏（sash）颜色。** &nbsp; 
可在自定义界面配置肩形标题栏（sash）的配色和不透明度。<br/>
关于静态和动态界面，及如何配置操作按钮的更多内容，请参看[WatchKit Programming Guide](https://developer.apple.com/library/prerelease/ios/documentation/General/Conceptual/WatchKitProgrammingGuide/index.html#//apple_ref/doc/uid/TP40014969)


