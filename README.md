# 像素转换器 (Pixel Converter) - 专业版

![Language](https://img.shields.io/badge/Language-HTML%2FJS%2FCSS-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Style](https://img.shields.io/badge/Style-Glassmorphism-blue)

像素转换器是一款现代、纯净且功能强大的 Markdown 与 HTML 双向转换工具。它采用单文件架构，无需安装，开箱即用，旨在为开发者和内容创作者提供最高效率的写作体验。

## ✨ 核心特性

- **🚀 双向转换**：完美支持 Markdown 到 HTML 的转换，以及 HTML 到 Markdown 的反向解析。
- **🔄 实时同步**：源码编辑器与可视化预览/撰写器之间实现毫秒级实时数据同步。
- **💎 现代 UI 设计**：采用高级磨砂玻璃 (Glassmorphism) 视觉风格，提供沉浸式的创作环境。
- **🛡️ 安全可靠**：内置 DOMPurify 净化引擎，严格过滤 XSS 攻击，确保内容输出安全。
- **📱 全平台适配**：响应式布局优化，完美支持手机、平板及 PC 端。
- **📦 单文件运行**：所有逻辑、样式和结构均集成在单一 HTML 文件中，极易部署和分发。

## 🛠️ 技术栈

- **Frontend**: Vanilla JS, Modern CSS (Custom Properties, Backdrop-filter)
- **Engine**: 
  - [marked.js](https://github.com/markedjs/marked) - 高性能 Markdown 解析
  - [turndown.js](https://github.com/mixmark-io/turndown) - 优雅的 HTML 转 Markdown
  - [Quill.js](https://quilljs.com/) - 语义化的富文本编辑器
  - [DOMPurify](https://github.com/cure53/dompurify) - 工业级 XSS 过滤器

## 🚀 快速开始

1. 下载或复制代码库目录下的 `index.html`。
2. 在任意现代浏览器中直接打开 `index.html`。
3. **源码模式**：直接并在左侧输入 Markdown 或 HTML 代码，右侧将实时呈现预览。
4. **可视化编写**：切换至“可视化编写”标签页，像使用 Word 一样进行富文本创作。

## 📖 使用指南

- **复制功能**：底部操作栏提供了“复制 HTML”和“复制 Markdown”按钮，一键获取目标格式。
- **同步数据**：在可视化模式下完成创作后，点击“同步至源码模式”可更新原始数据。
- **清空内容**：点击“清空全部”快速重置当前工作空间。

## 📄 开源协议

本项目基于 MIT 协议开源。
