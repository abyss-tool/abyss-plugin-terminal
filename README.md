<div align="center">

# 🖥 终端引擎

### Termux 血统的内置 Linux 终端：黑底白字 / 快捷命令键盘 / 前台服务保活，深渊工具的灵魂模块。

[![Plugin CI](https://github.com/Ultra-Guru/abyss-plugin-terminal/actions/workflows/plugin-ci.yml/badge.svg?branch=main)](https://github.com/Ultra-Guru/abyss-plugin-terminal/actions/workflows/plugin-ci.yml)
![Version](https://img.shields.io/badge/version-0.1.0-7EC8FF)
![Category](https://img.shields.io/badge/分类-终端-4FD8EB)
![Status](https://img.shields.io/badge/状态-框架预览-1A222D)

</div>

---

> 深渊工具（[Ultra-Guru/Abyss-Tools](https://github.com/Ultra-Guru/Abyss-Tools)）的终端类大插件 —— 本仓库为**插件框架期骨架**：manifest / 补丁通道 / CI 门禁已就绪，插件本体按路线图实现。

## 插件信息

| 字段 | 值 |
| --- | --- |
| 插件 ID | `abyss-plugin-terminal` |
| 分类 | 终端（terminal） |
| 版本 | v0.1.0（框架预览） |
| 最低宿主 | App v0.1.0 / HOST_API v1 |
| 仓库 | [Ultra-Guru/abyss-plugin-terminal](https://github.com/Ultra-Guru/abyss-plugin-terminal) |
| 补丁通道 | [`patches/index.json`](patches/index.json) |

## 权限需求

- `INTERNET`
- `FOREGROUND_SERVICE`
- `WAKE_LOCK`


## 安装

经深渊工具主壳「导航 → 插件 → 插件中心」安装（安装 AP 流水线：下载 →
SHA-256 校验 → 安装网关）。**APK 资产自 v0.2 发布流水线起发布** —— 当前
仓库发布 manifest 与补丁通道骨架。

## 补丁更新

- 通道：本仓库 `patches/index.json`（abyss-plugin-patches-v1）
- 引擎：主壳 `abyss-patch-v1` 数据补丁（下载 → SHA-256 → 备份 → 应用 → 失败回滚）
- 插件详情页实时展示补丁时间线

## 路线图

- [ ] v0.2 伪终端渲染内核（VT/ANSI）
- [ ] v0.3 bootstrap 根文件系统
- [ ] v0.4 快捷命令键盘与主题工坊

## 许可

受限许可（UGRL v1.0）：仅供个人学习与安全研究，禁止再分发与商业使用 —— 见 [LICENSE](LICENSE)。
