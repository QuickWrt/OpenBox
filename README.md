# 🧰 QuickWrt - OpenBox

![OpenWRT Version](https://img.shields.io/badge/OpenWRT-v24.10-blue.svg)
![License](https://img.shields.io/badge/License-GPLv3-green.svg)
![Platform](https://img.shields.io/badge/Platform-x86_64%20%7C%20Rockchip-orange)
![Build](https://img.shields.io/badge/Status-Stable-success.svg)

**QuickWrt OpenBox** 是 [QuickWrt](https://github.com/QuickWrt/QuickWrt) 的核心配置仓库，  
用于存放 OpenWRT 自动化构建系统所需的 **定制化配置文件、编译模板和附加软件包**。  
它让 QuickWrt 构建系统能够在不同架构间快速切换、灵活扩展，并提供丰富的个性化特性。

---

## 🌟 功能简介

- 🧩 **多架构支持**：包含 x86_64 与 Rockchip 的配置模板  
- ⚙️ **模块化配置**：独立的 `config/`、`scripts/`、`package/` 子系统  
- 🚀 **编译优化**：集成加速构建机制与工具链缓存支持  
- 🧠 **自动适配**：根据架构自动选择目标配置  
- 🧱 **可扩展设计**：可直接复用或接入第三方构建系统（如 Lede / ImmortalWRT）

---
