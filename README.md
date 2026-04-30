# FRP Manager

FRP Manager 是一个基于 C++ 开发的轻量级 Windows 客户端，旨在为 [frp](https://github.com/fatedier/frp) 提供简洁直观的图形化管理界面。

## 功能特点
* **双模式支持**：同时管理 `frpc` 客户端与 `frps` 服务端。
* **双语切换**：原生支持 **中文** 与 **英文** 界面，自动跟随系统语言。
* **状态监控**：实时显示服务的运行或停止状态。
* **规则预览**：主界面直接提取并展示 `.toml` 配置中的核心转发规则。
* **开机自启**：支持随系统启动自动运行，实现内网穿透无人值守。
* **原生轻量**：基于 Win32 API 开发，无额外运行时依赖，资源占用极低。
* **系统兼容**：完美兼容 Windows 7/10/11 以及 Windows Server 各版本。

## 界面预览

### 主界面 (中/英对照)
| 中文界面 (Chinese) | 英文界面 (English) |
| :--- | :--- |
| ![ZH](https://github.com/user-attachments/assets/1f8f4ede-80cf-479f-ac1c-cf9adb846ad5) | ![EN](https://github.com/user-attachments/assets/e5a7b152-4792-4f95-9873-f2e1d985b353) |

### 设置页面
![Settings](https://github.com/user-attachments/assets/f25a1aac-74d7-42fb-8394-acb17917df3c)

## 使用说明
1. 点击 **设置 (Settings)** 选择包含 `frpc.exe` 或 `frps.exe` 的 FRP 程序根目录。
2. 点击 **编辑配置 (Edit Config)** 修改对应的 `.toml` 规则。
3. 点击 **启动 (Start)** 开始运行服务。
4. 勾选 **开机启动 (Auto-Start)** 开启自动化运行。

## 编译信息
* **开发工具**: Visual Studio 2022 (v143)
* **开发语言**: C++ 20
* **核心框架**: 原生 Win32 API

## 开源协议
MIT License
