<div align="center">

# Qoder Switcher

面向 Qoder 的本机多账号加速网关 · 安装包下载

[![Version](https://img.shields.io/github/v/release/726599757/qoder-switcher-releases?display_name=tag&style=flat-square)](https://github.com/726599757/qoder-switcher-releases/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-0ea5e9?style=flat-square)](https://github.com/726599757/qoder-switcher-releases/releases)

本仓库**只有安装包**，没有源码。到 [Releases](https://github.com/726599757/qoder-switcher-releases/releases) 下载对应系统的文件。

</div>

> [!NOTE]
> 安装包未签名。Windows 可能被 SmartScreen 拦截；macOS 请右键打开，或执行 `xattr -cr` 后再启动。

| 系统 | 文件 |
| --- | --- |
| Windows | `QoderSwitcher-<版本>-windows-amd64.exe` |
| Linux | `QoderSwitcher-<版本>-linux-amd64.AppImage` |
| macOS（Apple Silicon） | `QoderSwitcher-<版本>-darwin-arm64.dmg` |

校验：同一 Release 里的 `SHA256SUMS.txt`。

Linux：`chmod +x *.AppImage` 后运行。无 FUSE 时：`APPIMAGE_EXTRACT_AND_RUN=1 ./QoderSwitcher-*.AppImage`。
