# Ink Canvas Teaching
基于 InkCanvasForClass 的代码开发的一个屏幕书写应用。

## 为什么选择本应用？
InkCanvasForClass 是一个非常好的项目，我作为一个网管，在班上的一体机长期使用，可惜 InkCanvasForClass 的开发者 doubi906w 目前已经几乎停止维护他的项目，因此我想来接手这个项目，为该项目贡献一份活力。Ink Canvas Teaching 则是 InkCanvasForClass 的延续。该项目基于 icc-0610fix 的代码进行优化与修改，合入了许多 InkCanvasForClass 最新版本中的功能。目前正在尝试和开发者取得联系，并尝试加入许多 icc-private 中的功能。

## 说明与亮点

1. **更加稳定高效** : Ink Canvas Teaching 使用了和 希沃白板5 相同的窗口透明显示原理，让运行效率更高，体验更加流畅。同时还使用了许多来自 希沃白板5 的源码中的黑科技来优化稳定性。
2. **部分使用 Golang 开发** : Ink Canvas Teaching 的部分功能和部分应用界面使用了 Golang 和 miqt 开发。
3. 基础的屏幕书写，白板批注功能。
4. 悬浮窗拦截、自动查杀、自动收纳、自动跳转（打开其他软件自动关闭并打开本应用的指定功能）
5. 几何绘图功能：可以绘制 ICC 中的绝大部分立体几何图形和平面几何图形，而且支持动态调整。正方形支持在绘制时自动贴边对齐，椭圆支持在绘制时自动矫正圆心与辅助同心等距绘制。
6. 智能绘图辅助：自动拉直直线（支持多指），形状识别（使用单独的.NET Framework进程，且会对墨迹分析库返回的数据进行优化）。
7. PPT联动模式：支持在 PPT 放映时显示翻页按钮，支持选中 PPT 上的图片，文本元素进行移动，缩放，翻转等功能，支持放映 PPT 时弹出 移除自动播放和移除隐藏幻灯片 的弹窗。
8. **移除内置的计时器、抽奖、回放功能** : 为了将 Ink Canvas Teaching 打造成一个 纯粹的屏幕书写软件，Ink Canvas Teaching 将不会内置 计时器和抽奖功能。
9. 支持多屏幕书写，支持 UIAccess 置顶和自动定时抢占置顶，使用全局键盘钩子监听与拦截键盘事件，支持无焦点批注窗口。

## 开发者

LyinWuWo
