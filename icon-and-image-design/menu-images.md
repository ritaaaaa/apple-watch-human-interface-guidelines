# 菜单图片 - Menu Images

Force Touch 菜单中的 icon 是模板图片，由图片的 Alpha Channel 定义生成。因此图片中的颜色信息会被忽略。

使用菜单图片，图片的 canvas 尺寸应大于内容的尺寸，如 Table 21-1 所示。内容周围的额外空间可确保菜单 icon 边缘和内容之间有足够的边界。

**Table** 21-1 Canvas and content sizes for menu images
<table>
    <tbody>
        <tr>
            <th>Device</th>
            <th>Canvas size</th>
            <th>Content size</th>
        </tr>
        <tr>
            <td>Apple Watch(38mm)</td>
            <td>70 pixels</td>
            <td>46 pixels</td>
        </tr>
        <tr>
            <td>Apple Watch(42mm)</td>
            <td>80 pixels</td>
            <td>54 pixels</td>
        </tr>
    </tbody>
</table>

**请使用适合设备尺寸和符号复杂度的线宽。**符号所用线条的宽度不能少于 4px，以免难以辨认。具体请参考 Figure 21-1.

**Figure 21-1** Glyph sizes for menu images

![image](../images/menu_glyphs_2x.png)

**推荐使用 PNG 格式的菜单图片**，但要避免使用交叉处理的 PNG 图片。
