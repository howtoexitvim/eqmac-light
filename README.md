# eqMac Light 🎵

<p align="center">
  <b><a href="#english">English</a></b> | <b><a href="#chinese">简体中文</a></b>
</p>

---

<a name="english"></a>
## English 🇬🇧

eqMac Light is a custom, lightweight, and **zero-ad** fork of the classic eqMac audio equalizer for macOS. 

This version was created because we got tired of getting badgered to upgrade to "Pro" every time we adjusted our volume or plugged in headphones.

### 🚫 Features
* **Ad-Free & Pro-Free:** No upgrade popups, no subscription prompts, and no premium advertisements. Just raw audio control.
* **Offline & No OTA:** We blocked web-based Over-The-Air updates. The app loads clean, offline UI assets directly from the bundle. No remote tracking.
* **No Auto-Switch Noise:** Removed the intrusive headphone auto-enable/disable logic. Your audio routing stays exactly where you set it.
* **macOS 15 Sequoia Ready:** Fully signed and optimized to bypass Library Validation blocks inside the system `coreaudiod` process.

### 🛠️ How to Build
1. Clone this repository:
   ```bash
   git clone https://github.com/howtoexitvim/eqmac-light.git
   cd eqmac-light/native
   ```
2. Install CocoaPods dependencies:
   ```bash
   pod install
   ```
3. Open `eqMac.xcworkspace` in Xcode, select your signing certificate, and hit **Build**.

---

<a name="chinese"></a>
## 简体中文 🇨🇳

eqMac Light 是一个专为 macOS 打造的、定制轻量级且**完全无广告**的经典 eqMac 音频均衡器分支版本。

开发这个版本的初衷，是作者受够了每次调节音量或插拔耳机时，原版软件不断弹出升级到 "Pro" 专业版的烦人广告。

### 🚫 特色功能
* **无广告无付费提示：** 彻底去除所有专业版升级弹窗、订阅诱导和商业广告，还你清爽的音频体验。
* **离线化 & 屏蔽 OTA 自动更新：** 禁用网页端 OTA 自动更新，强制加载本地离线 UI 资源，不与任何广告服务器通信。
* **移除耳机自动切换干扰：** 删除了原版逻辑中容易出错的耳机插拔自动切换设置，音频通道保持绝对稳定。
* **完美适配 macOS 15 Sequoia：** 解决 macOS 15 下 Library Validation 对第三方插件的严苛限制，绝不导致 `coreaudiod` 音频驱动进程崩溃。

### 🛠️ 如何编译
1. 克隆本仓库：
   ```bash
   git clone https://github.com/howtoexitvim/eqmac-light.git
   cd eqmac-light/native
   ```
2. 安装 CocoaPods 依赖：
   ```bash
   pod install
   ```
3. 使用 Xcode 打开 `eqMac.xcworkspace`，选择你自己的开发证书，点击 **Build** 编译即可。
