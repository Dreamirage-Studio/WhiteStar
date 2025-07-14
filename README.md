# WhiteStar 工具箱

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
[![.NET](https://img.shields.io/badge/.NET-8.0-purple.svg)](https://dotnet.microsoft.com/)
[![Language](https://img.shields.io/badge/Language-中文-red.svg)](README.md)

> 🌟 现代化的 Windows 工具集合，提供截图、录屏、标注等实用功能

## 📖 简介

WhiteStar 工具箱是一个功能强大的 Windows 桌面工具集合，专为提高工作效率而设计。采用现代化的 Aero 风格界面，支持多语言，提供直观易用的操作体验。

### ✨ 主要特性

- 🎯 **智能启动器** - 可收缩的浮动工具栏，位于屏幕左下角
- 🖼️ **截图工具** - 快速截取屏幕区域，支持编辑和保存
- 📝 **标注工具** - 在屏幕上添加文字、箭头、图形等标注
- 🎥 **录屏工具** - 高质量屏幕录制，支持多种格式
- 🌐 **多语言支持** - 支持中文、英文多种语言

## 🚀 快速开始

### 系统要求

- **操作系统**: Windows 10/11 (x64)
- **运行时**: .NET 8.0 Runtime
- **内存**: 最少 512MB RAM
- **存储**: 50MB 可用空间

### 下载地址

| 版本类型 | 文件名 | 大小 | 说明 |
|---------|--------|------|------|
| 🔧 **安装版** | `WhiteStar_Setup.exe` | ~740KB | 推荐，包含完整安装向导 |

### 安装方式

#### 方式一：安装包（推荐）
1. 下载 `WhiteStar_Setup.exe`
2. 右键选择"以管理员身份运行"
3. 按照安装向导完成安装
4. 选择所需组件（桌面快捷方式、开机启动等）
5. 安装完成后自动启动


## 📸 界面预览

### 智能启动器
- **收缩状态**: 仅显示触发块，节省屏幕空间
- **展开状态**: 显示所有工具，5×6 网格布局
- **中文界面**: 默认显示中文工具名称

### 工具界面
- **现代设计**: Aero 风格，支持高斯模糊
- **直观操作**: 简洁明了的用户界面
- **响应式布局**: 适配不同屏幕分辨率

## 🛠️ 功能介绍

### 📱 智能启动器
- **位置**: 屏幕左下角，贴边显示
- **状态**: 支持展开/收缩，节省屏幕空间
- **操作**: 点击触发块展开工具栏
- **固定**: 启动器位置固定，不可拖动

### 🖼️ 截图工具
- **快速截图**: 选择区域快速截取
- **编辑功能**: 添加文字、箭头、矩形等
- **保存格式**: 支持 PNG、JPG、BMP 格式
- **快捷键**: 支持自定义快捷键

### 📝 标注工具
- **实时标注**: 在任意应用上方添加标注
- **多种工具**: 画笔、文字、箭头、图形
- **颜色选择**: 丰富的颜色和样式选项
- **透明背景**: 不影响底层应用操作

### 🎥 录屏工具
- **高质量录制**: 支持 1080p 高清录制
- **音频录制**: 可选择录制系统音频
- **格式支持**: MP4、AVI 等主流格式
- **压缩优化**: 智能压缩，文件小质量高

## 🎮 使用指南

### 首次启动
1. 安装完成后，程序会自动启动
2. 启动器出现在屏幕左下角
3. 默认为中文界面
4. 程序最小化到系统托盘

### 基本操作
- **展开启动器**: 点击左下角的触发块
- **选择工具**: 点击对应的工具图标
- **切换语言**: 点击"语言设置"按钮
- **退出程序**: 右键系统托盘图标选择"退出"

### 快捷操作
- **双击托盘图标**: 显示/隐藏启动器
- **右键托盘图标**: 显示上下文菜单
- **ESC 键**: 在工具中取消当前操作

## ⚙️ 配置选项

### 安装选项
- ✅ **主程序** - 核心功能（必选）
- ⚪ **桌面快捷方式** - 在桌面创建快捷方式
- ⚪ **开始菜单快捷方式** - 在开始菜单创建程序组
- ⚪ **开机自启动** - 系统启动时自动运行

### 语言设置
- 🇨🇳 **简体中文** - 默认语言
- 🇺🇸 **English** - 英语界面


## 📁 文件结构

```
WhiteStar/
├── WhiteStar.exe              # 主程序
├── AnnotationTool.exe         # 标注工具
├── ScreenshotTool.exe         # 截图工具
├── graphics/
│   └── app_icon.ico          # 应用图标
├── license.txt               # 许可协议
└── 相关 DLL 文件
```

## 🔧 技术规格

- **开发框架**: .NET 8.0 + WPF
- **界面风格**: Modern Aero Design
- **支持架构**: x64
- **安装包大小**: ~740KB
- **运行内存**: ~50MB
- **启动时间**: <2秒

## 🔍 常见问题

### Q: 程序无法启动怎么办？
A: 请确保已安装 .NET 8.0 Runtime，并以管理员权限运行。

### Q: 如何卸载程序？
A: 通过控制面板的"程序和功能"或运行安装目录下的 `uninst.exe`。

### Q: 支持哪些操作系统？
A: 支持 Windows 10 和 Windows 11 (x64 架构)。

### Q: 如何更改界面语言？
A: 点击启动器中的"语言设置"按钮，选择所需语言。

### Q: 录屏文件保存在哪里？
A: 默认保存在用户的"视频"文件夹中，可在设置中修改。

## 🛡️ 安全说明

- 程序需要屏幕录制权限用于截图和录屏功能
- 不会收集或上传任何用户数据
- 所有文件均保存在本地
- 开源代码，安全透明

## 📋 更新日志

### v1.0.8 (2024-12-XX)
- ✨ 首次发布
- 🎯 智能启动器设计
- 🖼️ 截图工具完整功能
- 📝 标注工具基础功能
- 🎥 录屏工具集成
- 🌐 多语言支持

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request


## 📞 联系我们

- **项目主页**: [GitHub Repository](https://github.com/Dreamirage-Studio/WhiteStar))
- **问题反馈**: [Issues](https://github.com/Dreamirage-Studio/WhiteStar/issues)

## 🙏 致谢

感谢所有为 WhiteStar 工具箱做出贡献的开发者和用户！

## ⭐ Star History
[![Star History Chart](https://api.star-history.com/svg?repos=Dreamirage-Studio/WhiteStar&type=Date)](https://www.star-history.com/#Dreamirage-Studio/WhiteStar&Date)

---

<div align="center">

**⭐ 如果这个项目对您有帮助，请给我们一个 Star！⭐**

Made with ❤️ by Dreamirage Studio

</div>
