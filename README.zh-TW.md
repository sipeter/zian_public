[English](readme.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# zian - 本機優先的離線語音輸入工具

PC **v0.9.7.0**：[下載與更新說明](https://github.com/sipeter/zian_public/releases/tag/v0.9.7.0)。手機端 Link 維持 v0.9.5.0。

> 讓語音留在自己的裝置上。
>
> 在任何輸入框中直接以語音輸入，也可以將手機作為電腦的無線麥克風。

## 產品介紹

zian ([ziansoft.com](https://ziansoft.com)) 是一款適用於 Windows 的本機語音輸入與轉寫工具。

語音辨識在電腦本機完成，不依賴雲端語音辨識服務。你可以用它撰寫文件、聊天、輸入程式碼，或轉寫較長的音訊與影片檔案。

zian 同時提供 Android 與 iOS 版 ZianLink，讓手機透過區域網路連接電腦，成為 zian 的無線麥克風。

## 主要功能

- **本機語音輸入**：預設按住 `CapsLock` 說話，放開後將文字輸入目前視窗；快速鍵可自行調整。
- **四款本機辨識模型**：內建 SenseVoice，可視需要安裝 FunASR Nano、Qwen3-ASR 0.6B / 1.7B；提供 CPU 與 NVIDIA GPU 版本。
- **統一模型管理**：在設定中下載、匯入離線 ZIP、驗證及移除選用模型；應用程式更新保留獨立模型目錄。
- **輸入校正與本機規則**：快速校正最近輸入的文字，將常用修改儲存為本機規則，並可叫回最近一句。
- **zian Scribe 檔案轉寫**：支援音訊與影片檔案轉寫、批次處理、進度顯示、結果預覽與匯出。
- **ZianLink 手機麥克風**：Android 手機與 iPhone 可透過區域網路作為電腦麥克風；Android 支援「按住錄音」與「點按錄音」。
- **多種文字輸出方式**：支援剪貼簿貼上與模擬鍵盤輸入，可依編輯器、聊天工具或遊戲選擇合適方式。
- **可選文字整理**：視需要使用標點處理、自訂規則與 AI 輔助潤飾。
- **使用者主動檢查更新**：只在使用者主動操作時檢查更新，不會在背景靜默檢查。

## 隱私說明

zian 的語音辨識核心在本機執行，不會為了雲端辨識而上傳錄音或轉寫內容。

授權啟用、使用者主動檢查更新及可選模型下載等功能可能會存取網路。手機麥克風音訊透過區域網路傳輸，並由電腦上的本機模型處理。

## 平台支援

### Windows

- Windows 10 / 11 64 位元
- 提供 CPU 與 NVIDIA GPU 版本
- 提供安裝版與綠色可攜版
- 建議至少 8 GB 記憶體
- .NET Framework 4.7.2 或更新版本

### Android - ZianLink

- 將 Android 手機作為 PC 端 zian 的無線麥克風
- 支援按住錄音與點按錄音
- 透過 Google Play 或 APK 發佈

### iOS - ZianLink

- 將 iPhone 作為 PC 端 zian 的無線麥克風
- 支援錄音控制與輸入完成回饋
- IPA 必須簽名後才能安裝

## 快速開始

1. 下載適合電腦的 CPU 或 GPU 版本。
2. 使用安裝程式安裝，或將綠色版解壓縮到不含特殊字元的路徑。
3. 執行 `Zian.exe`，等待右下角的系統匣圖示出現。
4. 在任何輸入框中按住 `CapsLock` 說話，放開後即可輸入文字。
5. 如需使用手機麥克風，請在電腦端啟用 ZianLink，再使用手機連接電腦。

## 下載與社群

- 官方網站：https://ziansoft.com
- Discord：https://discord.gg/tQqecuFW
- QQ 交流群：1034895071

## 授權

zian 是商業軟體。你可以在 **設定 → 授權管理** 中啟用授權。

本專案使用的開源元件及其授權資訊，請參閱軟體包中的 `THIRD-PARTY-NOTICES.txt`。

---

Copyright © 2026 Zian. All Rights Reserved.
