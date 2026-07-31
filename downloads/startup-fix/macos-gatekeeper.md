---
layout: page
title: Launching Acycle on an Apple Silicon Mac
permalink: /downloads/startup-fix/macos-gatekeeper/
---

## Content / 内容

1. English Instructions: Launching Acycle on an Apple Silicon Mac
2. 中文说明：在 Apple 芯片 Mac 上启动 Acycle

## English Instructions

If macOS displays:

> “Acycle_3_0” is damaged and can’t be opened. You should move it to the Trash.

The message may be caused by the macOS Gatekeeper quarantine attribute rather than actual file corruption. Proceed only when Acycle was downloaded from an official or trusted source.

### 1. Move the app to Applications

Fully extract the downloaded archive, then move:

```text
Acycle_3_0.app
```

to:

```text
/Applications
```

Do not run the app directly from a ZIP archive, the Downloads folder, or a disk image.

### 2. Remove the quarantine attribute

Open Terminal and run:

```shell
xattr -dr com.apple.quarantine "/Applications/Acycle_3_0.app"
```

Press Return, then reopen Acycle.

To avoid typing the path incorrectly, enter:

```shell
xattr -dr com.apple.quarantine
```

Leave a space at the end, drag `Acycle_3_0.app` from Finder into the Terminal window, and press Return.

### 3. If Terminal reports “Permission denied”

Run:

```shell
sudo xattr -dr com.apple.quarantine "/Applications/Acycle_3_0.app"
```

Enter your Mac login password and press Return. No characters will appear while the password is being typed; this is normal.

Finally, launch Acycle again from the Applications folder. If the app name or version number is different, use its actual filename and path.

---

## 中文说明：在 Apple 芯片 Mac 上启动 Acycle

### Acycle 3.0.2 - macOS M Chip 启动修复

### 适用环境

- Apple M Chip
- Acycle 3.0.2
- MATLAB Runtime R2026a Update 4

如果 macOS 提示：

> “Acycle_3_0”已损坏，无法打开。你应该将它移到废纸篓。

这通常可能是 macOS 的安全隔离机制导致的，并不一定表示程序文件真的损坏。请确认 Acycle 来自官方或可信来源，再按以下步骤操作。

### 1. 将 App 移入“应用程序”

先完整解压下载文件，然后把：

```text
Acycle_3_0.app
```

拖入：

```text
/Applications
```

不要直接从压缩包、下载文件夹或磁盘映像中运行。

### 2. 移除下载隔离标记

打开 Terminal（终端），输入：

```shell
xattr -dr com.apple.quarantine "/Applications/Acycle_3_0.app"
```

按回车后，重新打开 Acycle。

为避免路径或名称输入错误，也可以先输入：

```shell
xattr -dr com.apple.quarantine
```

注意末尾保留一个空格，然后把 `Acycle_3_0.app` 从 Finder 拖入终端窗口，再按回车。

### 3. 如果提示权限不足

运行：

```shell
sudo xattr -dr com.apple.quarantine "/Applications/Acycle_3_0.app"
```

输入 Mac 登录密码并按回车。输入密码时终端不会显示字符，这是正常现象。

随后在 Finder 的“应用程序”文件夹中重新启动 Acycle。若 App 名称或版本号不同，请使用实际文件名和路径。
