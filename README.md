# iPasteLite

**[English](#english) | [中文](#中文)**

---

<a id="english"></a>

# iPasteLite

**A lightweight, privacy-first clipboard manager for macOS. Just 2.1 MB.**

iPasteLite runs silently in your menu bar, automatically recording everything you copy — text and images — so you can find and reuse it instantly with a single hotkey.

## Download

**[Latest Release](https://github.com/iPasteLite/iPasteLite-Release/releases)**

Requires macOS 12.0+

## Features

### Lightning Fast

- **Global Hotkey** `Cmd + Shift + V` — summon clipboard history from anywhere, instantly.
- **0.75s polling** — near-instant capture of every copy action.
- **In-memory caching** — recent items loaded into memory for zero-lag browsing; configurable cache size.
- **Smart deduplication** — identical content is promoted to the top without creating duplicates.
- **Two display modes** — Classic horizontal layout or Concise vertical split-panel, switchable anytime.

### Privacy & Security

- **100% local** — no network requests, no telemetry, no data leaves your machine.
- **AES-256-GCM encryption** — all clipboard content (text and images) is encrypted before being written to the database.
- **XChaCha20-Poly1305** — settings and premium data use an additional authenticated encryption layer.
- **Keychain-stored secrets** — encryption keys are managed via macOS Keychain, never written to disk.
- **Configurable auto-expiry** — set independent retention periods for text and image history; expired items are automatically purged.
- **Signature verification** — config files are cryptographically signed to prevent tampering.
- **Password manager protection** — automatically ignores clipboard from 1Password, Bitwarden, LastPass, Dashlane, KeePassXC, Keeper, Enpass, RoboForm, and Password Safe.

### Convenient

- **Menu bar resident** — stays out of your way; toggle with hotkey or menu bar icon.
- **Concise mode** — a compact split-panel view with a searchable list and live preview, anchored near your cursor.
- **Smart search** — keyword search with context-aware excerpts that show surrounding lines for quick scanning.
- **Rich text preview** — preserves RTF formatting in the preview panel.
- **Image support** — captures and stores copied images with generated thumbnails for fast browsing.
- **Per-app analytics** — see which apps contribute the most to your clipboard, and selectively delete entries by app.
- **Bulk operations** — clear all history or selectively remove entries by app/type.

### Lightweight

- **Tiny installer** — just 2.1 MB, download and run in seconds.
- **Native Swift/Cocoa** — no Electron, no heavy runtime.
- **Adaptive memory** — automatically trims in-memory cache when the window is hidden.
- **Runs as accessory** — no Dock icon, no window clutter; purely a menu bar tool.

## Usage

1. Launch iPasteLite — it appears as an icon in the menu bar.
2. Copy anything as usual. iPasteLite captures it automatically.
3. Press `Cmd + Shift + V` to open the clipboard history panel.
4. Click or press Enter on any item to paste it.
5. Use the search field to filter by keyword.
6. Open Settings (from the menu bar) to configure retention, display mode, and more.

## Community

- [Telegram Group](https://t.me/+pMD76Cd_Oq85YjE1)
- [Feedback](https://t.me/+pMD76Cd_Oq85YjE1)

## License

Copyright &copy; 2023-2026 liw003. All rights reserved.

---

<a id="中文"></a>

# iPasteLite

**轻量、安全的 macOS 剪贴板管理工具。仅 2.1 MB。**

iPasteLite 静默运行在菜单栏，自动记录你复制的所有文本和图片，一键快捷键即可快速查找和复用。

## 下载

**[最新版本](https://github.com/iPasteLite/iPasteLite-Release/releases)**

需要 macOS 12.0 或更高版本

## 功能亮点

### 极速响应

- **全局快捷键** `Cmd + Shift + V` — 随时随地呼出剪贴板历史。
- **0.75 秒轮询** — 近乎实时捕获每一次复制操作。
- **内存缓存** — 最近条目常驻内存，浏览零延迟；缓存大小可配置。
- **智能去重** — 相同内容自动置顶，不产生重复记录。
- **双显示模式** — 经典横排布局或简洁竖排分栏，随时切换。

### 隐私安全

- **完全本地** — 无网络请求、无数据上报，数据绝不离开你的设备。
- **AES-256-GCM 加密** — 所有剪贴板内容（文本和图片）写入数据库前均经过加密。
- **XChaCha20-Poly1305** — 设置和高级会员数据额外使用一层认证加密。
- **钥匙串存储密钥** — 加密密钥通过 macOS 钥匙串管理，不会明文写入磁盘。
- **自动过期清理** — 可分别设置文本和图片的保留时间，过期条目自动清除。
- **签名校验** — 配置文件经过加密签名，防止篡改。
- **密码管理器保护** — 自动忽略 1Password、Bitwarden、LastPass、Dashlane、KeePassXC、Keeper、Enpass、RoboForm、Password Safe 等密码管理器的剪贴板内容。

### 便捷易用

- **菜单栏常驻** — 不打扰你的工作，快捷键或菜单栏图标随时呼出。
- **简洁模式** — 紧凑的分栏视图，左侧可搜索列表，右侧实时预览，窗口跟随鼠标位置。
- **智能搜索** — 关键词搜索并显示上下文摘要，快速定位目标内容。
- **富文本预览** — 预览面板保留 RTF 格式。
- **图片支持** — 自动捕获并存储复制的图片，生成缩略图方便浏览。
- **按应用统计** — 查看各应用的剪贴板贡献，支持按应用选择性删除。
- **批量操作** — 一键清空所有历史记录，或按应用/类型选择性删除。

### 轻量精简

- **安装包仅 2.1 MB** — 下载即用，秒级完成。
- **原生 Swift/Cocoa** — 无 Electron，无重型运行时。
- **自适应内存** — 窗口隐藏后自动收缩内存缓存。
- **纯菜单栏运行** — 不占 Dock 栏，无窗口干扰。

## 使用方法

1. 启动 iPasteLite，菜单栏会出现图标。
2. 正常复制内容，iPasteLite 会自动记录。
3. 按 `Cmd + Shift + V` 打开剪贴板历史面板。
4. 点击或按回车即可粘贴选中项。
5. 使用搜索框按关键词过滤。
6. 点击菜单栏图标进入「设置」，可配置保留时间、显示模式等。

## 社区

- [Telegram 群组](https://t.me/+pMD76Cd_Oq85YjE1)
- [意见反馈](https://t.me/+pMD76Cd_Oq85YjE1)

## 许可证

Copyright &copy; 2023-2026 liw003. 保留所有权利。
