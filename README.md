# BandClass-WearStore

表盘包 ZIP 根目录必须包含 `style.json`，背景图可选。`style.json` 支持 `theme`、`backgroundColor`、`primaryColor`、`secondaryColor`、`accentColor`、`align`（left/center/right）、`verticalPosition`（top/center/bottom）、`backgroundImage`（相对路径）、`backgroundOpacity`（0–100）、`cornerRadius`、`showClock`、`showDate`、`showSeconds`，以及 `progress` 对象（`enabled`、`color`、`opacity`）。图片使用 ZIP 内的相对路径，背景图建议控制在 2 MB ZIP 上限内。

`testThemes/ZWearTheme` 是完整示例；更新文件后请同步重建 `testThemes/package.zip`。
