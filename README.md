# 极光词典 AuroraDict

**完全离线、免费、快速的 Windows 英汉 · 汉英桌面词典。**

单文件、免安装、不依赖任何第三方运行库。内置 **326 万英文词条**与 **12 万中文词条**，自研检索内核，毫秒响应；本地查不到时可在线翻译回退，并支持一键自动更新。

![平台](https://img.shields.io/badge/platform-Windows%2010%2F11-3b82f6)
![版本](https://img.shields.io/badge/version-1.0.0-22d3ee)
![离线](https://img.shields.io/badge/works%20offline-yes-8b5cf6)
![许可](https://img.shields.io/badge/license-Free%20Software-green)

---

## ✨ 功能特性

- **完全离线**：词库本地存储，断网照常使用；不收集任何个人数据。
- **海量词库**：3,268,005 英文词条（含词形变化、短语、星级、考试标签）+ 121,408 中文词条（含拼音、繁体、多释义）。
- **自研内核**：检索、Trie 索引、中文分词、拼写纠错、词形还原全部自研，零第三方运行库。
- **精美卡片**：音标、星级、考试标签（牛津 3000 / 高考 / 四六级 / 考研 / 托福 / GRE）、词形变化、中英双释义。
- **在线回退**：本地未收录且有网络时，自动尝试在线翻译；可在设置中关闭。
- **自动更新**：启动时后台检查最新版本，一键下载并自动完成替换（也可手动检查）。
- **生词本与复习**：收藏生词、闪卡复习，支持导出纯文本与 Anki（TSV）牌组。
- **离线发音**：英文、中文双语音，基于 Windows 内置语音合成。
- **快捷取词**：全局热键 `Ctrl+Alt+D`，可选复制后自动查词。
- **深浅色主题**：自绘界面，浅色 / 深色自由切换。

## 📥 下载与安装

前往 **[Releases 页面](https://github.com/haoeastspeed/AuroraDict/releases/latest)** 下载最新版本：

- 下载 `AuroraDict.exe`
- 双击即可运行，无需安装、无需联网（界面名称为「极光词典」）

**系统要求**：Windows 10 / 11（64 位），需 .NET Framework 4.0 或更高版本（系统通常已自带）。

## 🔄 自动更新

软件在启动时会后台检查本仓库的最新 Release（可在「设置 → 软件更新」中关闭）。发现新版本后会提示并自动下载、替换、重启；整个过程无需手动操作。若网络直连较慢，会自动尝试本地代理。你也可以随时在设置页点击「检查更新」。

## 🔒 隐私说明

- 词典数据与个人设置（生词本、历史记录）均保存在本机，不上传服务器。
- 仅在「本地无结果且开启在线回退」或「检查更新」时才会发起网络请求；离线时不发起任何请求。

## 📖 数据来源

- 英文词库：[ECDICT](https://github.com/skywind3000/ECDICT)（MIT License）
- 中文词库：[CC-CEDICT](https://www.mdbg.net/chinese/dictionary?page=cc-cedict)（CC BY-SA 3.0）
- 在线翻译：MyMemory 免费接口（仅在线回退时使用）

## 🏠 产品主页

<https://haoeastspeed.github.io/AuroraDict/>

---

© 2026 极光词典 AuroraDict。本软件免费提供使用。
