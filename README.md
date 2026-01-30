# MD2File

**一个极简、纯本地、且支持响应式的 Markdown 转 PDF 与长图工具。** **A minimalist, local-only, and responsive Markdown-to-PDF/Image converter.**

---

## 📖 简介 / Introduction

**MD2File** 是一个专为隐私和效率设计的轻量级网页工具。它无需安装，无需后端服务器，所有转换逻辑均在你的浏览器本地完成。它支持精确的 PDF 打印规格设置，并能模拟各种移动设备宽度以生成高清长图。

**MD2File** is a lightweight web tool designed for privacy and efficiency. It requires no installation or backend server—all conversion logic happens locally in your browser. It supports precise PDF print specifications and can simulate various mobile device widths to generate high-definition long images.

---

## ✨ 核心特性 / Key Features

* **🔒 100% 隐私安全 / 100% Private**: 所有处理都在浏览器本地完成，你的文档绝不会离开你的设备。
*All processing is done locally in the browser; your documents never leave your device.*
* **🌍 语言切换 / Language Toggle**: 支持中英文界面一键切换。
*Support one-click switching between Chinese and English interfaces.*
* **🏷️ 智能命名 / Smart Naming**: 自动提取 Markdown 的第一行标题作为文件名，并自动附加分辨率后缀。
*Automatically extracts the first line of Markdown as the filename with resolution suffixes.*
* **📐 深度自定义 / Custom Dimensions**:
* **PDF**: 预设 A3/A4/A5/Letter，并支持自定义毫米 (mm) 规格。
*Presets for A3/A4/A5/Letter and support for custom mm dimensions.*
* **图片 / Image**: 提供主流手机宽度及社交媒体（Instagram/X/Weibo/小红书）分享尺寸。
*Presets for mobile widths and social media platforms.*


* **🌗 暗色模式 / Dark Mode**: 支持手动切换主题，导出长图时可保留当前配色风格。
*Manual theme switching; long images can be exported with the active color scheme.*
* **📱 响应式优化 / Mobile Optimized**: 针对手机端进行了深度布局优化，采用吸顶菜单设计，提升移动端写作与导出体验。
*Deeply optimized for mobile with a sticky header for better editing and exporting.*

---

## 🚀 快速开始 / Quick Start

1. **下载 / Download**: 下载本项目中的 `index.html` 文件。
*Download the `index.html` file from this repository.*
2. **打开 / Open**: 使用 Chrome, Edge, Safari 或 Firefox 等浏览器直接打开该文件。
*Open the file directly in any modern web browser.*
3. **转换 / Convert**: 在编辑器输入内容，在侧边栏配置规格，点击导出即可。
*Type your content, configure the settings in the sidebar, and click export.*

---

## 🛠️ 技术栈 / Tech Stack

* [marked.js](https://github.com/markedjs/marked) - Markdown 解析 / Markdown parsing
* [html2pdf.js](https://www.google.com/search?q=https://github.com/eKoopmans/html2pdf.js) - PDF 渲染导出 / PDF rendering
* [html2canvas](https://github.com/niklasvh/html2canvas) - 网页长截图 / Web screenshots

---

## 📏 规格参考 / Specifications

### PDF 预设 / PDF Presets

| 预设 / Preset | 尺寸 / Dimensions | 用途 / Usage |
| --- | --- | --- |
| **A4** | 210 x 297 mm | 标准打印 / Standard Print |
| **A5** | 148 x 210 mm | 笔记手册 / Handbook |
| **Letter** | 216 x 279 mm | 美式信纸 / US Letter |

### 图片预设 / Image Presets

| 类别 / Category | 宽度 / Width | 建议场景 / Suggested For |
| --- | --- | --- |
| **Mobile** | 360px - 412px | 手机端阅读 / Mobile Reading |
| **Social (IG/WeChat)** | 1080px | 微信、Instagram |
| **Social (X/Twitter)** | 1200px | 推特分享 / X Sharing |
| **Social (Red/Weibo)** | 1500px | 微博、小红书 / Social Feeds |

---

## 📄 开源协议 / License

本项目基于 [MIT License](https://www.google.com/search?q=LICENSE) 协议开源。

*This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE).*
