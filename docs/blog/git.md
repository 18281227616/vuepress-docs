# Git 技术文档

## 目录
1. [Git 简介](#1-git-简介)
2. [安装与配置](#2-安装与配置)
3. [基础命令](#3-基础命令)
4. [分支管理](#4-分支管理)
5. [远程仓库](#5-远程仓库)
6. [高级操作](#6-高级操作)
7. [最佳实践](#7-最佳实践)
8. [常见问题](#8-常见问题)

---

## 1. Git 简介
Git 是一个分布式版本控制系统，由 Linus Torvalds 开发，用于高效管理项目代码。

### 核心概念
- **仓库（Repository）**：项目代码存储空间
- **提交（Commit）**：代码变更的快照
- **分支（Branch）**：独立的开发线
- **远程（Remote）**：云端代码仓库

---

## 2. 安装与配置

### 安装
```bash
# Ubuntu/Debian
sudo apt-get install git

# macOS
brew install git

# Windows
# 下载地址：https://git-scm.com/download/win

### 基础配置
# git config --global user.name "Your Name"
# git config --global user.email "your@email.com"
# git config --global core.editor "code --wait"  # 使用VSCode作为默认编辑器
