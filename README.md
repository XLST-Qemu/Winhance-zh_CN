# Winhance - Windows 增强实用程序 🚀

**Winhance** 是一款用于优化和自定义 Windows 体验的 PowerShell 图形用户界面应用程序。从软件管理到系统优化和自定义，Winhance 提供了增强 Windows 10 和 11 系统的功能。<br><br>**Winhance** 具有 [UnattendedWinstall](https://github.com/memstechtips/UnattendedWinstall) 几乎所有的相同增强功能，无需进行Windows的干净安装。

![image](https://github.com/user-attachments/assets/01b70777-f384-4ba4-8fc1-7dca81250f5a)

## 要求 💻
- Windows 11
  - *已测试 Windows 11 24H2*
  - *大多数东西应该能在 Windows 10 22H2 上正常工作，但存在一些问题*
- Windows PowerShell 5.1（预装在上述版本中）

## 使用说明 📜
要使用**Winhance**，请按照以下步骤以管理员身份启动PowerShell并运行安装脚本：

1. **以管理员身份打开PowerShell：**
   - **Windows 10/11**: 右键点击 **开始** 按钮并选择 **Windows PowerShell （管理员）** 或 **Windows 终端 （管理员）**
   - PowerShell 将在新窗口中打开。

2. **确认管理员权限**: 
   - 如果用户账户控制 (UAC) 提示，点击**是**以允许 PowerShell 以管理员身份运行。

3. **启用PowerShell脚本执行：**
   - 运行以下命令以允许脚本执行：
   ```powershell
   Set-ExecutionPolicy Unrestricted
   ```

4. **粘贴并运行命令**:
   - 复制以下命令：
   ```powershell
   irm "https://github.com/memstechtips/Winhance/raw/main/Winhance.ps1" | iex
   ```
   - 要粘贴到 PowerShell，请在 PowerShell 或终端窗口中**右键单击**或按**Ctrl + V**
   - 按下 **Enter** 执行命令

此命令将直接从GitHub下载并执行**Winhance**应用程序。

## 当前功能 🛠️

### 软件 & 应用 💿
- 安装软件
- 卸载 Windows 应用程序（永久删除）
  - Microsoft Edge
  - OneDrive
  - Recall
  - Copilot
  - Other Useless Windows Bloatware 

### 优化 🚀
- Set UAC Notification Level
- Disable or Enable Windows Security Suite
- Privacy Settings
- Gaming Optimizations
- Windows Updates
- Power Settings
- Scheduled Tasks
- Windows Services

### 自定义 🎨
- Toggle Windows Dark or Light Mode
- Taskbar Customization
- Start Menu Settings
- Explorer Options
- Notification Preferences
- Sound Settings
- Accessibility Options
- Search Configuration

### 关于 ⓘ
- About Winhance
- Author Socials
- Support Information
---
> [!NOTE]
- 此工具当前正在开发中。任何问题都可以通过“问题”标签报告。
- 此外，我不是开发者，我只是喜欢学习更多关于脚本/编程的知识，并在学习过程中不断进步。
- 也请理解我更喜欢独立开发和工作于这些项目。<br>我确实重视他人的见解并感谢任何反馈，但如果有拉取请求未被接受，请不要介意。

### 支持该项目

如果**Winhance**对您有帮助，请考虑支持该项目——这真的很有帮助！

[![Support via PayPal](https://img.shields.io/badge/Support-via%20PayPal-FFD700?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/memstech)

### 反馈与社区

如果您有反馈、建议，或需要 Winhance 的帮助，请加入我们在 GitHub 或 Discord 社区的讨论：

[![Join the Discussion](https://img.shields.io/badge/Join-the%20Discussion-2D9F2D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/memstechtips/Winhance/discussions)
[![Join Discord Community](https://img.shields.io/badge/Join-Discord%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://www.discord.gg/zWGANV8QAX)

### TODO:
- 为可以使用某些预设移除的应用程序创建单独/个别的复选框。 
- 实施修复“无法打开链接”问题的解决方案，原因是Edge已被移除。 
- 修复Windows 10上删除旧版MS Edge的问题。
- 实现用于长时间运行任务的后台作业。 
- 在Windows 10上实现更好的WinGet安装。
- 添加“创建Winhance桌面快捷方式”选项。
---
