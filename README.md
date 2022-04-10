# 拒绝强制亮度

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v1.0-green)
[![Telegram](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)

深夜拿起手机，不小心点到付款码、收款码、扫描二维码，屏幕亮度强制最高，人直接去世……

请给用户一个选择，拒绝 APP 强制屏幕亮度，从我做起。

## Developer

[酷安 @星夜不荟](http://www.coolapk.com/u/876977)

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

## 贡献

本模块使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI) 构建

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2019-2022 Fankes Studio(qzmmcn@163.com)