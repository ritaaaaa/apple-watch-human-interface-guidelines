# Icon 与图片尺寸 - Icon and Image Sizes

每个应用都需要一个漂亮的、令人难忘的主屏幕图标，便于用户更好地识别应用程序。由于用户仅仅通过主屏幕上的 icon 识别应用程序，所以你的 icon 应当是易于辨认的，且与 iOS app 的icon类似，能够良好地传达应用程序的目的。

![image](../images/HomeScreen_2x.png)

##Icon尺寸

主屏幕上的 icon 是圆形的。Table 20-1 列出了每个 icon 相应的直径（以像素为单位）和用途。所创建的图形资源都必须是 @2x 规格（注意：Xcode 中的 icon 尺寸是点）。

**Table 20-1** Icon sizes for WatchKit app on Apple Watch

<table>
    <tbody>
        <tr>
            <th>Asset</th>
            <th>Apple Watch(38mm)</th>
            <th>Apple Watch(42mm)</th>
        </tr>
        <tr>
            <td>Notification Center icon</td>
            <td>48 pixels</td>
            <td>55 pixels</td>
        </tr>
                <tr>
            <td>Long-Look notification icon</td>
            <td>80 pixels</td>
            <td>88 pixels</td>
        </tr>
                <tr>
            <td>Home Screen icon</td>
            <td>80 pixels</td>
            <td>80 pixels</td>
        </tr>
                <tr>
            <td>Short-Look icon</td>
            <td>172 pixels</td>
            <td>196 pixels</td>
        </tr>
    </tbody>
</table>

除了 WatchKit app 使用的 icon 之外，运行在用户 iPhone 上的 Apple Watch app 也需要一个相应的 icon。Table 20-2 列出了这些icon 资源的尺寸（以像素为单位）。同样，必须根据给定的尺寸创建图片资源。（注意：Xcode 中的 icon 尺寸是点）

**Table 20-2** Icon sizes for use by Apple Watch app on iPhone
<table>
    <tbody>
        <tr>
            <th>Asset</th>
            <th>@2x</th>
            <th>@3x</th>
        </tr>
        <tr>
            <td>App icon</td>
            <td>58 pixels</td>
            <td>87 pixels</td>
        </tr>
    </tbody>
</table>

**创建 icon 时，必须以指定尺寸创建完整的方形图片**，系统会自动为其添加圆形遮罩。

**对于所有的图片和 icon 来说，请使用 PNG 格式**，避免使用交叉处理的 PNG 图片。你可以使用带有索引颜色的 PNG 图片，以便节省图片文件中的空间。

**Icon 和图片必须使用标准色深（bit depth）**，标准色深(bit depth)为 24 位，也就是红、绿、蓝色各占用 8 位。icon 中不允许包含alpha channel。

##主屏幕上的icon
Apple Watch 的主屏幕非常独特，但也让人感到熟悉。主屏幕上的 icon 类似于 iOS app，但是不附带文本。在如此小的尺寸上，icon 必须清晰易于辨认，便于用户知道他们代表什么应用。如果 WatchKit app 的功能与其 iOS 上的 app 非常相似，那么icon要在视觉上保持一致。如果WatchKit app扮演的是辅助角色或者是 iOS app 的控制器时，icon 可以相应地有所不同。

**为了得到最佳效果，可以向专业平面设计师寻求帮助。**经验丰富的平面设计师可以帮助你打造 app 的整体视觉风格，并将该其应用到所有的 icon 和图片上。

**使用通用的用户易于辨识的意象。**通常要避免使用次要的或者语义模糊不清的元素。例如 Mail icon 通常会使用信封样式，而不是邮箱、邮递员的信件袋或者邮局标志。

**保持简洁。**特别要避免在 icon 中填塞大量不同的图形。尽可能找出某个能够捕捉应用精髓的单个元素，并能通过简单、独一无二的图形将其展示出来。注意请谨慎添加细节，如果 icon 的内容或形状过于复杂，那么在小尺寸屏幕上，这些细节会变得非常杂乱和模糊。

**为应用程序的主旨创建一个抽象的阐释。**通常以艺术的方式阐释现实会有更好的效果，这种方式可以强调出你希望用户关注的方面。

**确保 Apple Watch app 的 icon 和 iOS app 相似。**维持外观上的相似性能够帮助用户建立 WatchKit app 与 iOS app 之间的关联性。

**为不同屏幕尺寸的 Apple Watch 创建不同尺寸的主屏幕 app 图标。**确保 icon 在不同尺寸的 Apple Watch 设备上都能完美展示。关于设备尺寸规格，请参看 [Table 20-1](https://developer.apple.com/library/prerelease/ios/documentation/UserExperience/Conceptual/WatchHumanInterfaceGuidelines/IconandImageSizes.html#//apple_ref/doc/uid/TP40014992-CH16-SW2)。
