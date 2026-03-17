# 🐱 RedbeanCat v1.0 - 漫剧资产管理工具

<div align="center">

[![GitHub Release](https://img.shields.io/github/v/release/RedbeanCat/RedbeanCat)](https://github.com/RedbeanCat/RedbeanCat/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![.NET](https://img.shields.io/badge/.NET-8.0-blue.svg)](https://dotnet.microsoft.com/download/dotnet/8.0)

</div>

<div align="center">

一款基于.NET WinForms的开源漫剧资产管理工具，支持Save the Cat剧本结构、分镜管理、角色库和场景库。

</div>

---

## 🎯 功能清单

- ✅ Save the Cat剧本结构管理
- ✅ 分镜编号/时长/角度配置
- ✅ 角色库 (发型/服装/表情)
- ✅ 场景库 (背景/灯光/道具)
- ✅ OpenAI API调用
- ✅ 本地API接入 (Ollama/LocalAI)
- ✅ JSON导入导出
- ✅ 图片路径管理
- ✅ 批量处理

---

## 📦 系统要求

| 项目 | 要求 |
|------|------|
| **操作系统** | Windows 10/11 |
| **.NET版本** | .NET 8.0+ |
| **内存** | 2GB 可用内存 |
| **磁盘空间** | 50MB 可用空间 |

---

## 🚀 快速开始

### 方案A: 一键安装（推荐）

```bash
# 1. 克隆仓库
git clone https://github.com/RedbeanCat/RedbeanCat.git
cd RedbeanCat

# 2. 安装.NET Runtime（如果未安装）
winget install Microsoft.DotNet.SDK.8

# 3. 编译项目
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishSingleFile=true -o publish

# 4. 运行程序
publish\RedbeanCat.exe
