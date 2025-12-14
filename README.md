# Windows 软件安装脚本

## 系统工具更新

### 升级应用安装程序

升级 Windows 包管理器 (AppInstaller) 到最新版本

```powershell
winget upgrade --id Microsoft.AppInstaller --silent --accept-package-agreements --accept-source-agreements
```

### 升级 PowerShell

升级 PowerShell 核心版本

```powershell
winget upgrade --id Microsoft.PowerShell --silent --accept-package-agreements --accept-source-agreements
```

## 开发工具

### 安装 Windows Terminal

安装微软官方终端工具，支持多标签页和现代化界面

```powershell
winget install -e --id Microsoft.WindowsTerminal --silent --accept-package-agreements --accept-source-agreements
```

### 安装 Visual Studio Code

安装轻量级代码编辑器，支持多种编程语言

```powershell
winget install -e --id Microsoft.VisualStudioCode --silent --accept-package-agreements --accept-source-agreements
```

## 实用工具

### 安装 AB 下载管理器

安装功能强大的下载管理工具，支持多线程下载

```powershell
winget install -e --id amir1376.ABDownloadManager --silent --accept-package-agreements --accept-source-agreements
```

### 安装 PotPlayer

安装功能强大的多媒体播放器，支持多种视频格式

```powershell
winget install -e --id Daum.PotPlayer --silent --accept-package-agreements --accept-source-agreements
```

### 安装 7-Zip

安装压缩软件，支持多种压缩格式

```powershell
winget install -e --id 7zip.7zip --silent --accept-package-agreements --accept-source-agreements
```

## 通讯软件

### 安装 微信

安装微信

```powershell
winget install -e --id Tencent.WeChat --silent --accept-package-agreements --accept-source-agreements
```
