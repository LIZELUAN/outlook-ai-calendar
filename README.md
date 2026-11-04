# 🤖 AI Email-to-Calendar Converter / AI 邮件日历转换器

[English](#english) | [中文说明](#chinese)

---

<a name="chinese"></a>
## 🇨🇳 中文说明

一个基于大语言模型的单文件网页端 AI 工具，专为科研人员和高校师生设计。它可以将杂乱无章的学术讲座、研讨会邮件（如 Seminar、Grand Round 等）一键解析为结构化日程，支持一键导入 Outlook 网页版或生成 `.ics` 日历文件。

### ✨ 核心功能
* **全自定义 API 支持**：兼容所有 OpenAI 格式的接口。可在页面上自由配置 **API Base URL**、**API Key** 和 **模型名称**（支持 ChatAnywhere、DeepSeek、OpenAI 官方或自定义中转站）。
* **智能信息提取**：利用 AI 自动精准提取活动主题、演讲人/组织、起止时间、地点及简介。
* **学术标题规范**：自动识别并规范特定活动前缀（如 `Research Seminar: ...` 或 `Research Grand Round: ...`）。
* **智能时间兜底**：若邮件中仅给出日期或为多日活动，自动设定合理的默认全天时间（05:00 - 22:00）。
* **跨平台无缝适配**：
  * **💻 电脑端**：一键直达网页版 Outlook 日历编辑页。
  * **📱 手机端**：支持一键下载 `.ics` 文件（点开即可直接导入手机自带日历或 Outlook App）及复制摘要。
* **安全本地存储**：所有配置（URL、Key、Model）均通过浏览器的 `localStorage` 本地安全缓存，隐私绝对安全。

### 🚀 快速开始
👉 [点击这里打开在线工具](https://LIZELUAN.github.io/outlook-ai-calendar/)

---

<a name="english"></a>
## 🇬🇧 English

A standalone single-file web-based AI tool designed for researchers and academics. It parses unstructured academic seminar and event emails into structured calendar details, supporting one-click integration with Outlook Web and `.ics` file generation.

### ✨ Key Features
* **Fully Customizable API**: Compatible with any OpenAI-format API endpoints. Freely configure your **API Base URL**, **API Key**, and **Model Name** directly on the UI (supports ChatAnywhere, DeepSeek, OpenAI official, or custom proxies).
* **Smart Extraction**: Automatically extracts event titles, speakers/organizers, date/time, locations, and summaries.
* **Title Standardization**: Automatically prefixes titles for specific events (e.g., `Research Seminar: ...`, `Research Grand Round: ...`).
* **Intelligent Fallback**: Gracefully handles date-only or multi-day events with default sensible time windows (05:00 - 22:00).
* **Cross-Platform Support**:
  * **💻 Desktop**: One-click redirect to Outlook Web Calendar compose view.
  * **📱 Mobile**: One-click `.ics` file download (tap to import directly into Apple Calendar, Google Calendar, or Outlook Mobile App) and text copying.
* **Secure Local Storage**: All settings (URL, Key, Model) are safely stored locally via browser `localStorage`.

### 🚀 Usage
👉 [Open Your Web Tool Here](https://LIZELUAN.github.io/outlook-ai-calendar/)
