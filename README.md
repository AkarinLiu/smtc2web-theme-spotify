# smtc2web Spotify Theme

一个基于 Vue 3 的 Spotify 样式主题，用于 smtc2web。

![screenshot](screenshot.png)

## 更换字体

本主题不再内置字体文件，字体由用户在 smtc2web 设置界面中选择（需要 smtc2web v0.5.0 及以上版本）。

- 主题通过 CSS 变量 `var(--smtc-font-family, ...)` 应用用户选择的字体，fallback 为系统默认字体栈。
- 未配置字体时，自动使用系统已安装的字体（包括 CJK 字体）。
