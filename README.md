# Zafiro

> [!IMPORTANT]
> 本项目已迁移至 **[niki914/zafiro](https://github.com/niki914/zafiro)**，下载、文档与源码请前往主仓库。
>
> This project has moved to **[niki914/zafiro](https://github.com/niki914/zafiro)** — downloads, docs and source live in the main repo.

[![stars](https://img.shields.io/github/stars/Xposed-Modules-Repo/com.niki914.zafiro?label=stars)](https://github.com/Xposed-Modules-Repo/com.niki914.zafiro)
[![release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.niki914.zafiro?include_prereleases)](https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/releases/latest)
[![downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.niki914.zafiro/total)](https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/releases/latest)

<table align="center">
<tr>
<tr>
<td align="center"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/blob/main/res/zafiro__phone_use.gif?raw=true" alt="Zafiro device control demo" width="135" height="300"/></td>
<td align="center"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/blob/main/res/zafiro__net_research.gif?raw=true" alt="Zafiro web research demo" width="135" height="300"/></td>
<td align="center"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/blob/main/res/breeno_takeover__mcp.gif?raw=true" alt="Breeno takeover demo" width="135" height="300"/></td>
<td align="center"><img src="https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/blob/main/res/hyper_takeover__intro.gif?raw=true" alt="XiaoAi takeover demo" width="135" height="300"/></td>
</tr>
<tr>
<td align="center">Device Control</td>
<td align="center">Research</td>
<td align="center">Breeno Takeover</td>
<td align="center">XiaoAi Takeover</td>
</tr>
</tr>
</table>

> Android 原生 Agent——看懂屏幕、操控手机、跨应用完成任务，配备记忆、Skills、MCP 与 Python 运行时，还能通过 SSH 对接远程开发机。
>
> An Android native agent — reads your screen, controls your phone, and completes tasks across apps, with memory, Skills, MCP, and an on-device Python runtime. Connect to a remote dev machine via SSH.

Zafiro 是运行在 Android 手机上的智能 Agent。它具备完整的 Phone Use 能力：读取屏幕、点按、滑动、输入文字、打开应用，跨 App 完成操作。它能自行用 Python 封装工具来实现网络搜索、文件下载、网页阅读等能力，同时支持记忆、MCP 与 Skills。通过 [LSPosed](https://github.com/lsposed/lsposed) 接管系统语音助手（目前适配小布助手），用语音唤醒你自己的 Agent。设备暂不支持接管时，仍可使用 Zafiro 内置对话界面与全部 Agent 能力。

Zafiro is an intelligent agent running on your Android phone. It comes with full Phone Use capabilities: reading the screen, tapping, swiping, typing, and launching apps to complete operations across apps. It can wrap its own tools with Python for web search, file downloads, web page reading, and more, alongside memory, MCP, and Skills. Through [LSPosed](https://github.com/lsposed/lsposed), it takes over the system voice assistant (currently OPPO/OnePlus/Realme Breeno) — wake it by voice and your own Agent answers. When takeover is not supported on your device, the built-in chat interface with full Agent capabilities is always available.

- 源码 / Source: [niki914/zafiro](https://github.com/niki914/zafiro)
- 下载 / Download: [Releases](https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/releases/latest)
- 交流群 / Community: [Telegram](https://t.me/+ZPX2xtSl6RwyZGNl)
- 旧版源码 / Legacy source: [breeno-source-changer](https://github.com/Xposed-Modules-Repo/com.niki914.zafiro/tree/breeno-source-changer)
