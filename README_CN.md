# eqMac Light 🎵

[English](README.md)

eqMac Light 是专为 macOS 打造的一个轻量、纯净且无干扰的 eqMac 均衡器版本。

本项目专注于保留最核心的音频均衡功能，同时带来完全离线化、纯本地的界面体验。

### 🌟 主要特性
* **纯净的音频均衡体验：** 聚焦于基础均衡器（Basic EQ）核心功能，免去各种升级提示和付费注册弹窗。
* **完全离线运行：** 修改了 UI 加载机制，强制从 App 包体内读取本地静态资源，不请求外部网页，不进行 OTA 自动更新，无多余网络请求。
* **稳定的通道控制：** 移除了耳机插拔自动切换通道的逻辑，让你的音频输出设备始终保持在你设定的状态。
* **适配 macOS Sequoia：** 解决系统 `coreaudiod` 音频进程对外部驱动的 Library Validation 校验限制，运行更加稳定。

### 📸 软件截图
<p align="center">
  <img src="screenshots/menu.png" width="380" alt="eqMac Light 菜单" />
  &nbsp;&nbsp;
  <img src="screenshots/setting.png" width="380" alt="eqMac Light 设置" />
</p>

### 📥 下载安装
你可以直接在 [Releases](https://github.com/howtoexitvim/eqmac-light/releases) 页面下载预编译好的 `eqMac.app` 压缩包。解压后拖入 `/Applications` 文件夹即可直接运行。
