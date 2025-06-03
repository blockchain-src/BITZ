# ===BITZ 安装与启动指南===

## 🔴适用于 Linux、WSL、macOS 系统

- 首次安装并启动：请在终端执行以下命令（确保你已经安装了git）

```bash
git clone https://github.com/blockchain-src/BITZ.git && cd BITZ && chmod +x bitz.sh && sudo ./bitz.sh
```

- 后续启动：执行以下命令

```bash
bitz collect
```
## 🔴适用于 Windows 系统

- 首次安装并启动：请以管理员身份启动 PowerShell，依次执行以下命令（确保你已经安装了git）：

```powershell
Set-ExecutionPolicy Bypass -Scope CurrentUser
git clone https://github.com/blockchain-src/BITZ.git
cd BITZ
.\bitz_wins.ps1
```

- 后续启动：执行以下命令

```powershell
bitz collect
```
---

如有问题，请参考项目主页或提交 issue 获取帮助。