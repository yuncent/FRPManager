# FRP Manager

FRP Manager 是一个基于 C++ 开发的轻量级 Windows 客户端，用于图形化管理 [frp](https://github.com/fatedier/frp)。

## 功能特点
* **同时管理**：支持一键启停 frpc 客户端和 frps 服务端。
* **状态显示**：实时显示服务的运行或停止状态。
* **规则预览**：主界面直接读取并展示 .toml 配置文件中的核心转发规则。
* **开机自启**：支持随系统启动自动运行服务。
* **原生轻量**：基于 Win32 API 开发，无额外运行时依赖，占用资源极低。

## 界面预览

### 主界面 (中/英)
| 中文界面 | 英文界面 |
| :--- | :--- |
| ![ZH](https://github.com/user-attachments/assets/bd1dd4cc-954e-4ad9-8bd3-bdb9805dab69) | ![EN](https://github.com/user-attachments/assets/59d1834f-cc4e-4e65-98f5-65359d161d49) |

### 设置页面
![Settings](https://github.com/user-attachments/assets/ea2b3291-7a27-4b30-9b8f-83b70d09a460)

## 使用说明
1. 点击 **设置** 选择 FRP 程序所在的根目录。
2. 点击 **编辑配置** 修改对应的 .toml 文件。
3. 点击 **启动** 开始运行服务。
4. 勾选 **开机启动** 开启自动化运行。

## 编译信息
* **工具**: Visual Studio 2022 (v143)
* **语言**: C++ 20

## 开源协议
MIT License
