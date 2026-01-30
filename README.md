# MD2File

一个极简、纯本地、且支持响应式的 Markdown 转 PDF 与长图工具。  
A minimalist, local-only, and responsive Markdown-to-PDF/Image converter.

---

## 📖 简介 / Introduction

**MD2File** 是一个专为隐私和效率设计的轻量级网页工具。它无需安装，无需后端服务器，所有转换逻辑均在你的浏览器本地完成。它不仅支持标准的 A4 打印尺寸，还能模拟手机和社交媒体的宽度导出高清长图。

**MD2File** is a lightweight web tool designed for privacy and efficiency. It requires no installation or backend server—all conversion logic happens locally in your browser. It supports standard A4 printing sizes and can export high-definition long images optimized for mobile devices and social media.

---

## ✨ 核心特性 / Key Features

* **🔒 100% 隐私安全 / 100% Private**: 所有处理都在浏览器本地完成，你的文档绝不会被上传到任何服务器。
* **🏷️ 智能命名 / Smart Naming**: 自动提取 Markdown 的第一行标题作为文件名，并智能附加分辨率后缀。
* **📐 深度自定义尺寸 / Custom Dimensions**:
    * **PDF**: 预设 A3/A4/A5/Letter，支持自定义毫米 (mm) 规格。
    * **图片**: 模拟主流手机宽度及社交媒体（Instagram/X/Weibo/小红书）分享尺寸。
* **🌗 双色模式 / Dark Mode**: 支持手动切换深色/浅色主题，保护视力，导出长图可跟随主题色。
* **🌍 双语支持 / Bilingual**: 界面、下拉菜单以及默认初始化内容均支持中英文一键切换。
* **📱 响应式设计 / Responsive**: 完美适配桌面端、平板和移动端浏览器。在手机上会自动切换为垂直布局，方便触控操作。

---

## 🚀 快速开始 / Quick Start

1.  **下载 / Download**: 下载本仓库中的 `index.html` 文件。
2.  **打开 / Open**: 使用任何现代浏览器（Chrome, Edge, Safari, Firefox）直接打开 `index.html`。
3.  **转换 / Convert**: 在编辑器中输入 Markdown，在侧边栏选择你需要的规格，点击“导出”即可。

---

## 🛠️ 技术栈 / Tech Stack

* [marked.js](https://github.com/markedjs/marked) - 高效的 Markdown 解析
* [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) - 优质的 PDF 生成
* [html2canvas](https://github.com/niklasvh/html2canvas) - 网页高清长截图

---

## 📏 导出规格说明 / Export Specs

### PDF 预设
| 预设 / Preset | 尺寸 / Dimensions | 用途 / Usage |
| :--- | :--- | :--- |
| **A4** | 210 x 297 mm | 标准打印 / Standard Print |
| **A5** | 148 x 210 mm | 笔记手册 / Handbook |
| **Letter** | 216 x 279 mm | 美式信纸 / US Letter |
| **Custom** | 自定义 / Custom | 任意规格 / Any Size |

### 图片预设 / Image Presets
| 类别 / Category | 宽度 / Width | 建议场景 / Suggested For |
| :--- | :--- | :--- |
| **Standard Mobile** | 360px | 标准手机阅读 / Mobile Reading |
| **Large Mobile** | 412px | 大屏手机阅读 / Large Screens |
| **Social (Square)** | 1080px | 微信、Instagram / WeChat, IG |
| **Social (X)** | 1200px | X (Twitter) |
| **Social (Red)** | 1500px | 微博、小红书 / Weibo, Red Book |

---

## 📄 开源协议 / License

本项目基于 [MIT License](LICENSE) 协议开源。
