# DeepElectron Harness (DE-Harness)

[English](README.md) | 中文

**DeepElectron Harness**（`de-harness`）是 [DeepSeek Harness (`dsh`)](https://github.com/deepseek-ai/deepseek-harness) 的 GUI 桌面化实现。

我们通过 Electron 框架将原生的 CLI / 脚本化工具改造为开箱即用、跨平台的桌面端软件。它保留了原项目由 [Cordis](https://github.com/cordiverse/cordis) 驱动的**一切皆插件**架构，同时赋予其直观的现代图形界面与本地原生体验。

---

## ✨ 桌面化特性

- 🖥️ **图形化控制台**：告别命令行，提供开箱即用的 GUI 界面，轻松配置参数与调度 Agent。
- 📦 **跨平台原生支持**：基于 Electron 构建，完整适配 macOS、Windows 和 Linux。
- 🔒 **本地安全存储**：API Key 及敏感配置均在本地加密存储，网络请求与数据完全掌握在自己手中。
- 👁️ **过程可视化**：清晰展现模型思考过程（Chain-of-Thought）、工具调用（Function Calling）步骤及上下文状态。
- ⚡ **系统级深度集成**：支持系统托盘常驻、快捷键唤醒、文件拖拽解析与本地桌面通知。

---

## 🚀 快速开始

### 下载安装包（适合普通用户）

前往项目的 [Releases](../../releases) 页面，下载对应操作系统的最新安装包：

- **macOS**: `.dmg` / `.zip` (支持 Apple Silicon 及 Intel 芯片)
- **Windows**: `.exe` 安装包 / 便携版
- **Linux**: `.AppImage` / `.deb` 包

---

## 🛠️ 从源码开发与构建

适合希望自行从源码编译或进行二次开发的开发者。

### 环境要求

- [Node.js](https://nodejs.org/) `>= 18.0.0`
- [pnpm](https://pnpm.io/) `>= 8.0.0`

### 1. 克隆仓库

```sh
git clone [https://github.com/your-username/deepseek-electron-harness.git](https://github.com/your-username/deepseek-electron-harness.git)
cd deepseek-electron-harness
