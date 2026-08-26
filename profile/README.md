<p align="center">
  <a href="https://github.com/dsh-tauri-desk/deepseek-harness-desktop">
    <img src="https://raw.githubusercontent.com/dsh-tauri-desk/deepseek-harness-desktop/main/public/favicon.svg" width="96" alt="DeepSeek Harness Desktop" />
  </a>
</p>

<h1 align="center">DeepSeek Harness Desktop</h1>

<p align="center">
  将 <a href="https://github.com/deepseek-ai/deepseek-harness">DeepSeek Harness</a> 封装为简单易用的原生桌面应用，下载即用。
</p>

<p align="center">
  <a href="https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases"><img src="https://img.shields.io/github/v/release/dsh-tauri-desk/deepseek-harness-desktop?style=flat-square&label=release&color=4D6BFE" alt="Release" /></a>
  <a href="https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases"><img src="https://img.shields.io/github/downloads/dsh-tauri-desk/deepseek-harness-desktop/total?style=flat-square&label=downloads&color=4D6BFE" alt="Downloads" /></a>
  <a href="https://github.com/dsh-tauri-desk/deepseek-harness-desktop/blob/main/LICENSE"><img src="https://img.shields.io/github/license/dsh-tauri-desk/deepseek-harness-desktop?style=flat-square&label=license" alt="License" /></a>
  <img src="https://img.shields.io/badge/Windows%20%7C%20macOS%20%7C%20Linux-black?style=flat-square" alt="Windows | macOS | Linux" />
</p>

<p align="center">
  <a href="https://github.com/dsh-tauri-desk/deepseek-harness-desktop">下载桌面版</a> ·
  <a href="https://github.com/dsh-tauri-desk/deepseek-harness-desktop/blob/main/README.md">文档</a> ·
  <a href="https://github.com/dsh-tauri-desk/deepseek-harness-desktop/issues">反馈问题</a>
</p>

---

我们是一个 **DeepSeek Harness 的非官方、非商业开源社区组织**，专注于把 Harness 做成更轻量、更顺手的原生桌面体验：

- **零环境启动**：无需预装 Node.js、pnpm 或 Docker，安装后即可运行。
- **跨平台桌面应用**：基于 Tauri 2，支持 Windows、macOS 与 Linux。
- **内核与档案管理**：在应用内管理 Harness 版本、配置档案和隔离环境。
- **插件生态**：通过插件扩展侧边栏、通知、终端检查和工作流能力。
- **本地优先**：应用和 Harness 在本机运行，尽量保持数据与开发环境可控。

## 项目

| 项目 | 说明 |
| --- | --- |
| [deepseek-harness-desktop](https://github.com/dsh-tauri-desk/deepseek-harness-desktop) | DeepSeek Harness 跨平台桌面发行版 |
| [dsh-tauri](https://github.com/dsh-tauri-desk/dsh-tauri) | DSH 插件与 Tauri 2 外壳之间的通信桥接 |
| [dsh-tauri-ui](https://github.com/dsh-tauri-desk/dsh-tauri-ui) | 面向 Tauri 外壳的设置侧边栏与界面组件 |
| [dsh-tauri-worktree](https://github.com/dsh-tauri-desk/dsh-tauri-worktree) | 为会话创建隔离 Git Worktree 的插件 |
| [deepseek-harness-pkg](https://github.com/dsh-tauri-desk/deepseek-harness-pkg) | 预打包 Harness 内核与发行资源 |
<!-- | [dsh-tauri-rightclick](https://github.com/dsh-tauri-desk/dsh-tauri-rightclick) | 原生风格上下文菜单扩展 | -->

## 使用

前往 [Releases](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases) 下载对应平台的安装包。桌面版会负责准备运行环境并启动本地 Harness，首次运行需要网络下载运行时与内核资源。

如果你使用 macOS，也可以通过 Homebrew 安装：

```bash
brew install dsh-tauri-desk/desktop/deepseek-harness
```

## 参与贡献

欢迎提交 Issue、改进文档、贡献代码或制作社区插件。开始前请先阅读目标仓库的贡献指南和安全说明；插件与第三方代码请在安装前自行审阅来源。

- [报告 Bug / 提交功能建议](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/issues)
- [浏览全部仓库](https://github.com/orgs/dsh-tauri-desk/repositories)
- [查看桌面版开发文档](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/tree/main/docs)

> [!NOTE]
> 本组织与 DeepSeek、DeepSeek AI 或 DeepSeek Harness 上游项目没有官方隶属关系。DeepSeek Harness 具备本地代码执行能力，请只在可信、隔离的环境中使用。

<p align="center">
  <sub>Built by the dsh-tauri-desk community · MIT licensed where stated by each project</sub>
</p>
