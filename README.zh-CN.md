[English](readme.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# zian - 本地优先的离线语音输入工具

PC **v0.9.7.0**：[下载与更新说明](https://github.com/sipeter/zian_public/releases/tag/v0.9.7.0)。手机端 Link 保持 v0.9.5.0。

> 让语音留在自己的设备上。
>
> 在任意输入框中直接说话输入，也可以使用手机作为电脑的无线麦克风。

## 产品介绍

zian ([ziansoft.com](https://ziansoft.com)) 是一款面向 Windows 的本地语音输入与转写工具。

语音识别在电脑本地完成，不依赖云端语音识别服务。你可以用它撰写文档、聊天、输入代码，或者转写较长的音频和视频文件。

zian 同时提供 Android 和 iOS 版 ZianLink，让手机通过局域网连接电脑，作为 zian 的无线麦克风。

## 主要功能

- **本地语音输入**：默认按住 `CapsLock` 说话，松开后将文字输入当前窗口；热键可以自行调整。
- **四款本地识别模型**：内置 SenseVoice，可按需安装 FunASR Nano、Qwen3-ASR 0.6B / 1.7B；提供 CPU 和 NVIDIA GPU 版本。
- **统一模型管理**：在设置中下载、导入离线 ZIP、校验和卸载可选模型；应用升级保留独立模型目录。
- **上屏纠错与本地规则**：快速纠正最近输入的文字，将常用修改保存为本地规则，并可召回最近一句。
- **zian Scribe 文件转写**：支持音频和视频文件转写、批量处理、进度查看、结果预览与导出。
- **ZianLink 手机麦克风**：Android 和 iPhone 可以通过局域网作为电脑麦克风；Android 支持“按住录音”和“点按录音”。
- **多种文字输入方式**：支持剪贴板粘贴和模拟键盘输入，可根据编辑器、聊天工具或游戏选择合适方式。
- **可选文字整理**：按需使用标点处理、自定义规则和 AI 辅助润色。
- **用户主动检查更新**：仅在用户主动操作时检查更新，不在后台静默检查。

## 隐私说明

zian 的语音识别核心在本机运行，不会为了云端识别而上传录音或转写内容。

许可证激活、用户主动检查更新以及可选模型下载等功能可能访问网络。手机麦克风的音频通过局域网传输，并由电脑上的本地模型处理。

## 平台支持

### Windows

- Windows 10 / 11 64 位
- 提供 CPU 和 NVIDIA GPU 版本
- 提供安装版和绿色便携版
- 建议至少 8 GB 内存
- .NET Framework 4.7.2 或更高版本

### Android - ZianLink

- 将 Android 手机作为 PC 端 zian 的无线麦克风
- 支持按住录音和点按录音
- 通过 Google Play 或 APK 分发

### iOS - ZianLink

- 将 iPhone 作为 PC 端 zian 的无线麦克风
- 支持录音控制和输入完成反馈
- IPA 需要签名后才能安装

## 快速开始

1. 下载适合电脑的 CPU 或 GPU 版本。
2. 使用安装程序安装，或将绿色版解压到不含特殊字符的目录。
3. 运行 `Zian.exe`，等待右下角托盘图标出现。
4. 在任意输入框中按住 `CapsLock` 说话，松开后即可输入文字。
5. 如需使用手机麦克风，在电脑端开启 ZianLink，并使用手机连接电脑。

## 下载与社区

- 官方网站：https://ziansoft.com
- Discord：https://discord.gg/tQqecuFW
- QQ 交流群：1034895071

## 授权

zian 是商业软件。你可以在 **设置 → 授权管理** 中激活许可证。

本项目使用的开源组件及其许可信息，请参阅软件包中的 `THIRD-PARTY-NOTICES.txt`。

---

Copyright © 2026 Zian. All Rights Reserved.
