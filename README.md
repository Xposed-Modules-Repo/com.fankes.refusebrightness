# 拒绝强制亮度

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v1.1-green)
[![Telegram](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)

深夜拿起手机，不小心点到付款码、收款码、扫描二维码，屏幕亮度强制最高，人直接去世……

请给用户一个选择，拒绝 APP 强制屏幕亮度，从我做起。

## 作用域说明

- 只需勾选你需要生效的 APP 即可

- 建议不要勾选系统应用以免发生异常

- 模块已对系统框架设置了黑名单，勾选也不会生效

## 作用域贡献

- Fork 项目后 [前往这里](https://github.com/Xposed-Modules-Repo/com.fankes.refusebrightness/blob/main/SCOPE) 贡献作用域。

> 目前已添加

- QQ(标准版)
- TIM
- 微信
- 支付宝

## 适配说明

- 只支持 LSPosed，请不要在其它管理器上激活模块，否则会不生效

- 理论最低 Android 版本没有限制，但是 LSPosed 最低支持到 Android 8.0

- 激活后的 APP 将失去设置指定 `Activity` 亮度的功能(目前设定)

## 开发中的功能(按需求人数决定)

- 支持根据系统特定亮度区间和指定 `Activity` 做出亮度调整功能，防止必要的设置不生效

- 可配合屏幕遮罩和 Android 12 下的极暗模式自动限制调整屏幕亮度

## 请勿用于非法用途

<h3>1.&nbsp本软件免费、由兴趣使然、仅供学习交流而开发，如果你是从其他不明来源的渠道付费得到本软件，则你已上当受骗，若发现欢迎向我们举报。</h3>

<h3>2.&nbsp未经本人许可，禁止转载、搬运本软件的安装包及源代码到 GitHub 以外的平台并提供下载链接。</h3>

## 项目推广

<!--suppress HtmlDeprecatedAttribute -->
<div align="center">
    <h2>嘿，还请君留步！👋</h2>
    <h3>这里有 Android 开发工具、UI 设计、Gradle 插件、Xposed 模块和实用软件等相关项目。</h3>
    <h3>如果下方的项目能为你提供帮助，不妨为我点个 star 吧！</h3>
    <h3>所有项目免费、开源，遵循对应开源许可协议。</h3>
    <h1><a href="https://github.com/fankes/fankes/blob/main/project-promote/README-zh-CN.md">→ 查看更多关于我的项目，请点击这里 ←</a></h1>
</div>

## 贡献

本模块使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI) 构建

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2019-2022 Fankes Studio(qzmmcn@163.com)
