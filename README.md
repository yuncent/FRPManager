
FRP Manager (FRP 管理器)
FRP Manager 是一个基于 C++ 开发的轻量级 Windows 桌面客户端，旨在为 frp 提供简洁直观的图形化管理界面。它支持同时管理 frpc (客户端) 和 frps (服务端)，并提供一键启动、配置文件快速编辑及开机自启功能。

✨ 主要功能
双模式支持：同时集成 frp 客户端 (frpc) 和服务端 (frps) 的管理。

状态实时监控：直观显示当前服务的运行状态（已停止/运行中）。

配置概览：在主界面直接预览 .toml 配置文件的核心参数（如服务器地址、端口转发映射、日志保留天数等）。

一键操作：支持独立启动或停止特定服务。

自动化管理：内置“开机启动”选项，实现无人值守运行。

多语言界面：原生支持中文和英文界面，自动适应系统环境。

便捷设置：支持自定义 FRP 核心程序根目录，内置日志清除及配置文件快速编辑入口。

📸 界面预览
主界面 (Main Interface)
<img width="495" height="630" alt="2" src="https://github.com/user-attachments/assets/bd1dd4cc-954e-4ad9-8bd3-bdb9805dab69" />
<img width="635" height="443" alt="3" src="https://github.com/user-attachments/assets/ea2b3291-7a27-4b30-9b8f-83b70d09a460" />

环境要求
Windows 7 或更高版本。

已下载对应版本的 frp 可执行文件。

使用步骤
指定路径：运行程序后，点击“设置 (Settings)”，在“FRP 根目录”中选择你存放 frpc.exe 和 frps.exe 的文件夹。

<img width="494" height="630" alt="en" src="https://github.com/user-attachments/assets/59d1834f-cc4e-4e65-98f5-65359d161d49" />

编辑配置：点击“编辑配置”，根据需求修改 frpc.toml 或 frps.toml。

启动服务：回到主界面，点击对应的“启动 (Start)”按钮。

自动运行：勾选“开机启动 (Auto-Start)”即可随系统启动。

🛠️ 编译说明
本项目使用 Visual Studio 2022 开发，基于 Win32 API 编写，无冗余依赖，生成的二进制文件体积极小。

⚖️ 开源协议
本项目采用 MIT License 开源。
