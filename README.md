# awesome-mygo-apps

> 基于 [egoist/mygo](https://github.com/egoist/mygo)（纯 Go 原生桌面 UI 框架）的**可运行应用与组件库**精选清单 —— 每条都经过 go.mod 依赖实证，可追溯、可复现。

![stars](https://img.shields.io/badge/stars-33%20recommended-F0544E)
![license](https://img.shields.io/badge/license-见各条目-lightgrey)
![collected](https://img.shields.io/badge/data%20collected-2026--10--26-green)
![PR Welcome](https://img.shields.io/badge/PR-welcome-brightgreen)

---

## 生态背景

[mygo](https://github.com/egoist/mygo) 是 2026 年 9 月发布的纯 Go 桌面 UI 框架：无 Electron、无 cgo，GPU 绘制原生 UI。截至 2026-10-26，已实测收录 **33 个**基于 mygo 的完整应用、UI 组件库与工具，全部经 go.mod 依赖实证。

## 目录

- [框架作者出品](#框架作者出品egoist)
- [完整应用](#完整应用)
  - [AI · 智能体](#ai--智能体)
  - [编辑器 · 笔记](#编辑器--笔记)
  - [网络 · 代理](#网络--代理)
  - [媒体 · 播放下载](#媒体--播放下载)
  - [生产力 · 菜单栏](#生产力--菜单栏)
  - [系统 · 监控](#系统--监控)
  - [游戏 · 趣味](#游戏--趣味)
- [UI 组件库](#ui-组件库)
- [贡献指南](#贡献指南)

---

## 框架作者出品（egoist）

mygo 作者 [egoist](https://github.com/egoist) 本人用自家框架写的应用，代表生态最高完成度：

- **[egoist/kero](https://github.com/egoist/kero)** — 面向 coding agent 的跨平台原生终端。⭐ 1223 · MIT
- **[egoist/gorex](https://github.com/egoist/gorex)** — Rex 终端克隆，`go tool mygo build` 出 .app/.dmg。⭐ 147 · 未声明 LICENSE
- **[egoist/godiff](https://github.com/egoist/godiff)** — 原生 diff 查看器。⭐ 126 · 无 LICENSE
- **[egoist/mygo-cloudmusic](https://github.com/egoist/mygo-cloudmusic)** — 第三方网易云音乐客户端。⭐ 52 · AGPL-3.0

---

## 完整应用

### AI · 智能体

- [fachrihawari/omaterm](https://github.com/fachrihawari/omaterm) — 并排跑 coding agent 的终端工作台，创建于框架同日。⭐ 3 · MIT · Release 0.9.1（2026-10-25）
- [sorrycc/CCGuanjia](https://github.com/sorrycc/CCGuanjia) — 照看 Claude Code 的 Mac 应用（profiles/checklists）。⭐ 3 · MIT · Release CCGuanjia 0.1.1（2026-10-22）

### 编辑器 · 笔记

- [sorrycc/Mayoi](https://github.com/sorrycc/Mayoi) — 迷い：Go 编写的小而快代码编辑器（GPU 原生 UI，无 webview/Electron，打包约 18MB）。⭐ 262 · MIT · Release Mayoi 0.12.0（2026-10-25）
- [echoVic/liubai](https://github.com/echoVic/liubai) — 留白：极简轻量 Markdown 写作桌（Go+MyGo 后端）。⭐ 4 · MIT · Release 留白 0.6.3（2026-10-23）
- [sorrycc/Deckle](https://github.com/sorrycc/Deckle) — macOS 快速原生 Markdown 编辑器（GPU 自绘界面）。⭐ 1 · MIT · Release Deckle 0.2.0（2026-10-16）

### 网络 · 代理

- [hygkui/v5vpn-rea-client](https://github.com/hygkui/v5vpn-rea-client) — 非官方 V5VPN/aTrust 客户端（协议逆向研究，自带免责声明）。⭐ 9 · Apache-2.0 · Release v0.6.0（2026-10-24）
- [xiaomai1011/GZIST-Hotspot](https://github.com/xiaomai1011/GZIST-Hotspot) — 校园网有线转热点（广州理工学院），中文项目。⭐ 4 · MIT · Release v2.0.0
- [sakurasan/clashx-go](https://github.com/sakurasan/clashx-go) — macOS 菜单栏 ClashX 风格代理客户端，内置 mihomo core。⭐ 1 · AGPL-3.0 · Release 0.2.6（2026-10-25）

### 媒体 · 播放下载

- [bitxeno/atvloadly](https://github.com/bitxeno/atvloadly) — ATV 视频下载器 + mygo 桌面壳。⭐ 1601 · AGPL-3.0 · Release v0.8.0
- [elianiva/meiro](https://github.com/elianiva/meiro) — 轻量 YouTube Music 客户端。⭐ 38 · GPL-3.0 · Release 0.4.10
- [zkeq/vibe-cook](https://github.com/zkeq/vibe-cook) — 烹饪教程 App（PWA + MyGo 桌面客户端）。⭐ 19 · 未声明 · Release v0.1.9（2026-10-25）
- [fazi-gondal/video-downloader-mygo](https://github.com/fazi-gondal/video-downloader-mygo) — yt-dlp/FFmpeg 桌面视频下载器。⭐ 1 · MIT · Release v3.0.0

> 另：[egoist/mygo-cloudmusic](https://github.com/egoist/mygo-cloudmusic)（网易云客户端）见 [框架作者出品](#框架作者出品egoist)。

### 生产力 · 菜单栏

- [henryyu333/shelf](https://github.com/henryyu333/shelf) — macOS 剪贴板管理，今日活跃。⭐ 57 · MIT · Release v1.9.0
- [Licoy/CPA-Bar](https://github.com/Licoy/CPA-Bar) — 菜单栏监控 CLIProxyAPI 服务。⭐ 13 · AGPL-3.0 · Release 1.0.12（2026-10-22）
- [oneo-me/neohm](https://github.com/oneo-me/neohm) — Home Assistant 菜单栏/托盘控制器（配套 onevra）。⭐ 9 · 未声明 · Release 0.2026.3（2026-10-20）
- [Beeta/voxi](https://github.com/Beeta/voxi) — macOS 会议录音转写/摘要助手。⭐ 1 · MIT · Release v0.7.0（2026-10-19）
- [FaintGhost/mac2mqtt](https://github.com/FaintGhost/mac2mqtt) — macOS 菜单栏 → Home Assistant over MQTT。⭐ 1 · MIT · Release v0.4.2（2026-10-25）
- [echoVic/clipnest](https://github.com/echoVic/clipnest) — 现代轻量 Mac 剪贴板历史面板（快捷键+预览）。⭐ 0 · MIT · Release Clipnest 0.1.4（2026-10-15）

### 系统 · 监控

- [echoVic/cleanzo](https://github.com/echoVic/cleanzo) — macOS 深度清理工具（安全优先，Go+MyGo 原生）。⭐ 9 · MIT · Release Cleanzo 0.2.5（2026-10-22）
- [RedwindA/gotify-desktop](https://github.com/RedwindA/gotify-desktop) — Gotify 推送接收桌面客户端，三平台。⭐ 5 · GPL-3.0 · Release v0.3.8（2026-10-24）
- [preceeder/gui-redis](https://github.com/preceeder/gui-redis) — 单机 Redis 桌面客户端（SSH 隧道/SOCKS5）。⭐ 1 · 未声明 · Release 0.1.1（2026-10-25）
- [smallnest/nutty](https://github.com/smallnest/nutty) — smallnest 出品的 macOS 原生终端（otty.sh clone）。⭐ 1 · Apache-2.0 · Release v0.2.0

> 另：[egoist/kero](https://github.com/egoist/kero)（agent 终端）、[egoist/gorex](https://github.com/egoist/gorex)（Rex 终端克隆）见 [框架作者出品](#框架作者出品egoist)。

### 游戏 · 趣味

- [echoVic/little-reef](https://github.com/echoVic/little-reef) — 小海底：用专注时间养出一片海的桌面挂件。⭐ 3 · MIT · Release 小海底 0.4.1（2026-10-24）
- [zhengchalei/leagueakari-mygo](https://github.com/zhengchalei/leagueakari-mygo) — 国服 LOL 战绩/选人助手（源自 LeagueAkari，monorepo 内 mygo/go.mod 实证）。⭐ 1 · MIT · Release v0.5.6

---

## UI 组件库

- [oneo-me/onevra](https://github.com/oneo-me/onevra) — 生态事实标准 Native UI 组件 + 打包器。⭐ 253 · MIT
- [smallnest/uix](https://github.com/smallnest/uix) — smallnest 出品组件库（同时依赖 onevra）。⭐ 21 · MIT
- [ELY-Open-Source/MujicaUI](https://github.com/ELY-Open-Source/MujicaUI) — 哥特风（Court-gothic）组件集。⭐ 12 · MIT
- [ELY-Open-Source/8bitMyGoUI](https://github.com/ELY-Open-Source/8bitMyGoUI) — 16-bit 像素风组件集（含 wasm 浏览器演示）。⭐ 8 · MIT
- [firede/mygo-platinum](https://github.com/firede/mygo-platinum) — 90 年代 Platinum 风格控件 + gallery。⭐ 1 · MIT · Release v0.2.1

---

## 贡献指南

欢迎 PR 补充 mygo 生态项目！收录门槛与审核流程见 [收录标准草案.md](./收录标准草案.md)（两步核验：依赖与门槛 → 内容与格式）。要点：

1. **go.mod 证据**：根目录（或 monorepo 内实际模块路径）`go.mod` 含 `require github.com/egoist/mygo ...`，PR 中附 raw 链接。
2. **star ≥ 1**。
3. 非空壳、用途一句话、license、最新 Release 或可运行说明。

PR 条目格式：`- [owner/repo](url) — 一句话描述。⭐ N · License · Release/可运行说明`