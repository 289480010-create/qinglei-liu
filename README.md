# Direct – 跨 App 快速跳转引擎 🔍

> **One Search. Direct Jump. Zero Waste.**  
> 让你在安卓手机上一键直达微信、小红书、淘宝等 App 的搜索页，告别反复翻找的历史信息。

![Demo GIF](https://via.placeholder.com/600x300?text=Direct+Demo) <!-- 替换为实际动图链接 -->
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 🚀 简介

你是否经常：
- 在微信聊天记录里翻了半天找一个文件？
- 忘记收藏的小红书笔记在哪？
- 想不起上次浏览的淘宝商品关键词？

**Direct** 是一款极简高效的安卓效率工具，它不是浏览器，也不是聚合阅读器，而是一个：

> 💡 **手机里的全局搜索引擎（Search Engine for Apps）**

输入关键词 → 显示多个 App 的可跳转入口 → 一点即达目标页面。

灵感源自 iOS 上的 [NoFeed](https://nofeed.app)，但专为安卓系统深度优化，支持更多中文主流 App。

---

## 🌟 核心特性

✅ **跨 App 搜索跳转**  
支持微信、小红书、淘宝、知乎、B站、京东、百度网盘、Notion 等 **15+ 主流 App**

✅ **零数据上传，隐私优先**  
所有配置本地存储，不收集搜索内容，不追踪用户行为

✅ **轻量快速，无广告**  
安装包 < 8MB，启动秒开，无任何商业化干扰

✅ **可扩展插件系统**（未来）  
支持社区贡献的 Deep Link 配置包，持续扩展新 App 支持

✅ **全局悬浮球呼出**  
在任意界面下滑或点击悬浮球，立即唤出搜索面板

---

## 📱 截图预览

| 主界面 | 悬浮球 | 设置页 |
|-------|--------|--------|
| ![Main](https://via.placeholder.com/270x600?text=Search+Panel) | ![Float](https://via.placeholder.com/270x600?text=Floating+Ball) | ![Settings](https://via.placeholder.com/270x600?text=Settings) |

> ⬆️ 实际使用效果更流畅！欢迎 PR 提交真实截图。

---

## 🛠️ 技术栈

- **语言**: Kotlin
- **UI**: Jetpack Compose
- **架构**: MVVM + Repository
- **核心机制**: Deep Link + Intent + AccessibilityService（可选）
- **数据管理**: Room + DataStore
- **依赖库**: Gson, AndroidX, Material 3

---

## 📦 如何构建？

### 1. 克隆项目
```bash
git clone https://github.com/yourname/Direct.git
cd Direct
