# 🪟 Windows 软件安装脚本

一键安装和管理 Windows 常用软件的 PowerShell 脚本集合。

---

## 📦 软件管理

### 升级所有软件

查看可升级的软件列表：

```powershell
winget upgrade
```

静默升级所有软件：

```powershell
winget upgrade --all --silent --accept-package-agreements --accept-source-agreements
```

---

## ⚙️ 系统工具

### Windows 包管理器 (AppInstaller)

升级 winget 到最新版本：

```powershell
winget upgrade --id Microsoft.AppInstaller --silent --accept-package-agreements --accept-source-agreements
```

### PowerShell

升级 PowerShell 核心版本：

```powershell
winget upgrade --id Microsoft.PowerShell --silent --accept-package-agreements --accept-source-agreements
```

---

## 💻 开发工具

### Windows Terminal

微软官方终端工具，支持多标签页和现代化界面。

```powershell
winget install -e --id Microsoft.WindowsTerminal --silent --accept-package-agreements --accept-source-agreements
```

### Visual Studio Code

轻量级代码编辑器，支持多种编程语言和丰富的插件生态。

```powershell
winget install -e --id Microsoft.VisualStudioCode --silent --accept-package-agreements --accept-source-agreements
```

---

## 🛠️ 实用工具

### AB 下载管理器

功能强大的下载管理工具，支持多线程下载和断点续传。

```powershell
winget install -e --id amir1376.ABDownloadManager --silent --accept-package-agreements --accept-source-agreements
```

### PotPlayer

功能强大的多媒体播放器，支持几乎所有视频格式。

```powershell
winget install -e --id Daum.PotPlayer --silent --accept-package-agreements --accept-source-agreements
```

### 7-Zip

开源压缩软件，支持多种压缩格式，压缩率高。

```powershell
winget install -e --id 7zip.7zip --silent --accept-package-agreements --accept-source-agreements
```

---

## 💬 通讯软件

### 微信

腾讯官方即时通讯工具。

```powershell
winget install -e --id Tencent.WeChat --silent --accept-package-agreements --accept-source-agreements
```

---

## 📝 使用说明

1. 以管理员身份运行 PowerShell
2. 复制所需的安装命令并执行
3. 所有命令均使用静默安装模式，无需手动点击

## 💡 提示

- 首次使用 winget 可能需要安装或更新 App Installer
- 建议定期运行 `winget upgrade --all` 保持软件最新
- 可以使用 `winget search <软件名>` 搜索更多软件

---
