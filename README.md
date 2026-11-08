<div align="center">

# QuickDict•闪查

### 一款为 Windows 打造的轻量级桌面词典

本地 77 万词条离线可查，联网自动补全例句与词源，整句短文也能翻译。

<p>
  <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white" alt="Platform: Windows">
  <img src="https://img.shields.io/badge/Architecture-x64-555555?style=for-the-badge" alt="Architecture: x64">
  <img src="https://img.shields.io/badge/.NET_Framework-4.8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET Framework 4.8">
  <img src="https://img.shields.io/badge/Version-4.0.0-2ea44f?style=for-the-badge" alt="Version 4.0.0">
</p>

<p>
  <a href="ms-windows-store://pdp/?productid=9NL7NFT20FKD">
    <img src="https://get.microsoft.com/images/zh-CN%20dark.svg" height="48" alt="从 Microsoft Store 获取">
  </a>
</p>

<p>
  <a href="#-功能特色">功能特色</a> ·
  <a href="#-下载与安装">下载与安装</a> ·
  <a href="#-技术栈">技术栈</a> ·
  <a href="#-开发状态">开发状态</a> ·
  <a href="#-反馈与建议">反馈与建议</a>
</p>

</div>

---

## ✨ 功能特色

### 查词与翻译

| 功能 | 说明 |
| --- | --- |
| 🔎 **快捷查词** | `Alt+Q` 全局唤出查词窗，输入即查；也支持托盘唤起，热键可自定义 |
| 📚 **离线词库** | 内置 ECDICT 77 万词条，断网也能查释义、音标、词性、考试标签 |
| 🔁 **词形与中文反查** | `ran`、`children` 自动指回原形；输入「苹果」可反查 apple |
| 🌐 **在线增强** | 联网补齐音标、柯林斯释义、双语例句、常见短语、同义反义、词源、词形变化 |
| 📄 **整句 / 短文翻译** | 一句话到 8000 字符整段，中英互译，译文置顶显示 |
| 🛩️ **离线翻译** | 内置本机翻译引擎，无网自动接管；翻译方式可选 自动 / 仅在线 / 仅离线 |
| 🔊 **单词发音** | 英音 / 美音在线发音，失败回退系统语音，离线也能出声 |
| 🖱️ **悬浮取词** | 按住 `Ctrl` 把鼠标停在生词上弹出释义卡片；选中一段文字可直接翻译 |

### 效率与工具

| 功能 | 说明 |
| --- | --- |
| ⭐ **收藏单词** | 星标收藏，列表直达词条详情，升级重装不丢 |
| 🕘 **历史记录** | 自动记录查过的词，本地加密存储，可一键清空 |
| 📥 **文件下载** | 粘贴链接即下载，分段并发、断点续传、完整性校验，不完整不算成功 |
| 🗜️ **万能解压缩** | ZIP / 7z / RAR / TAR / ISO，支持把压缩包直接拖进查词窗解压 |
| 📸 **截屏 / 录屏** | PNG 截图、MP4（H.264）录屏，默认存桌面，目录可改 |

### 界面与系统

| 功能 | 说明 |
| --- | --- |
| 🌗 **深色 / 浅色 / 跟随系统** | 三种模式，五套主题色（冰蓝、紫罗兰、翡翠绿、琥珀橙、玫瑰粉），字号实时可调 |
| 🪟 **可拖动查词窗** | 拖到任意位置并记住，换显示器或位置越界时自动回中 |
| ⚙️ **设置系统** | 百宝箱、收藏夹、外观、系统设置四大板块，改动即时生效 |
| 🚀 **开机自启与全局热键** | 一键开机启动；热键可改，被别的软件占用时自动换到可用组合 |
| 🧭 **首次启动引导** | 隐私同意书（含未满 14 周岁监护人确认）+ 5 页分步教学，可随时在设置里重看 |
| 🖥️ **Windows 桌面体验** | 常驻系统托盘、单实例运行，关闭查词窗不退出程序 |

## 📥 下载与安装

**方式一：微软商店（推荐，自动更新）**

<a href="ms-windows-store://pdp/?productid=9NL7NFT20FKD">
  <img src="https://get.microsoft.com/images/zh-CN%20dark.svg" height="52" alt="从 Microsoft Store 获取">
</a>

> 也可以在浏览器打开 [apps.microsoft.com/detail/9NL7NFT20FKD](https://apps.microsoft.com/detail/9NL7NFT20FKD)。

**方式二：GitHub Releases**

1. 前往 **[Releases](../../releases)** 下载最新版 `QuickDictSetup-x.y.z.exe`。
2. 运行安装程序，按向导完成安装（装到当前用户，无需管理员权限）。
3. 启动 QuickDict，按 `Alt+Q` 开始使用。

> 免安装版为 `QuickDict.exe` + `engine` 文件夹，整个目录拷走即可用；删除 `engine` 后离线翻译不可用，在线功能不受影响。

> **安全提示**
>
> 如果 Windows 显示“未知发布者”或 SmartScreen 安全警告，请先确认安装包来自本项目可信的官方发布渠道（Microsoft Store 或本仓库 Releases），再决定是否运行。

## 🛠️ 技术栈

| 项目 | 信息 |
| --- | --- |
| 开发框架 | WPF (C#) |
| 运行平台 | .NET Framework 4.8（系统自带，无需另装） |
| 目标系统 | Windows 10 2004 (19041) 及以上 / Windows 11 |
| 目标架构 | x64 |
| 本地词库 | ECDICT 77 万词条 + 自建词形 / 中文索引 |
| 离线翻译 | Argos Translate + CTranslate2 + SentencePiece（内嵌 Python 运行时） |
| 打包形式 | 免安装版 / 安装包 / MSIX（Microsoft Store） |

## 🚧 开发状态

QuickDict 是我的第一个软件项目，目前仍在持续开发与完善中。

我会逐步改进界面设计、功能体验、运行稳定性和软件更新机制。具体功能可能会随版本变化，请以实际发布版本为准。

## 💬 反馈与建议

遇到问题或有功能建议？欢迎通过 **[GitHub Issues](../../issues)** 提交反馈。

提问题时附上版本号（设置 → 系统设置 → 版本）和复现步骤，会更容易定位。

## 📄 许可与致谢

- 词库：[ECDICT](https://github.com/skywind3000/ECDICT)（MIT）
- 字体：Source Han Sans 思源黑体（SIL OFL 1.1）
- 离线翻译：[Argos Translate](https://github.com/argosopentech/argos-translate)（MIT）、[CTranslate2](https://github.com/OpenNMT/CTranslate2)（MIT）、[SentencePiece](https://github.com/google/sentencepiece)（Apache-2.0）；en→zh 模型源自 OPUS-MT，CC-BY-4.0
- 第三方许可全文随安装包分发

---

<div align="center">

**感谢你关注 QuickDict！**
如果这个项目对你有帮助，欢迎点亮 ⭐ Star 支持后续开发。

</div>
