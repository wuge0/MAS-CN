<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">Microsoft 激活脚本 (MAS)</h1>

<p align="center">开源的 Windows 和 Office 激活工具，支持 HWID、Ohook、TSforge、Online KMS 四种激活方式，并附带高级故障排查功能。</p>

<hr>
  
## 如何激活 Windows / Office / 扩展安全更新（ESU）？

### 方法一 - PowerShell ❤️

1. 点击 **开始菜单**，输入 `PowerShell` 并打开。

2. 复制下面的代码，粘贴后按 **回车键。**
   - 适用于 **Windows 8.1、10 和 11**：
     ```
     irm https://get.activated.win | iex
     ```
	 如果上面的地址被运营商/域名拦截了，试试这个（需要较新的 Windows 10 或 11）：
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
	 ```
	- **脚本跑不起来？改用下面的方法二。**

3. 在出现的菜单里，输入对应**绿色**选项的数字。

---

### 方法二 - 传统方式（Windows Vista 及以上）

1.   下载脚本：
      *   [**MAS_AIO.cmd**](https://github.com/wuge0/MAS-CN/raw/master/MAS/All-In-One-Version-KL/MAS_AIO.cmd)（直接脚本）
      *   [**MAS_AIO.zip**](https://github.com/wuge0/MAS-CN/archive/refs/heads/master.zip)（如果浏览器拦截了直接下载脚本）
2.   运行 `MAS_AIO.cmd` 文件。
3.   在出现的菜单里，输入对应**绿色**选项的数字。

---

> [!TIP]
> - 部分运营商/DNS 屏蔽了我们的域名，可以在浏览器里开启 [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) 来绕过。
> - **遇到问题**？访问[故障排查页](https://massgrave.dev/troubleshoot)，或在 [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/issues) 上提 issue。

> [!NOTE]
>
> - PowerShell 里的 `irm` 命令用于从指定 URL 下载脚本，`iex` 命令负责执行它。
> - 执行命令前务必核对 URL，手动下载文件时也要确认来源可信。
> - 警惕有人篡改 PowerShell 命令里的 URL，借此传播伪装成 MAS 的恶意软件。

---

<div align="center">
	
### 官网 - [https://massgrave.dev/](https://massgrave.dev/)
  
[![1.1]][1]
[![1.2]][2]
[![1.3]][3]
[![1.4]][4]
[![1.5]][5]
[![1.6]][6]
[![1.7]][7]

[1.1]: https://massgrave.dev/img/logo_discord.png (无需注册即可和我们聊天)
[1.2]: https://massgrave.dev/img/logo_reddit.png (Reddit)
[1.3]: https://massgrave.dev/img/logo_bluesky.png (Bluesky)
[1.4]: https://massgrave.dev/img/logo_x.png (Twitter)

[1.5]: https://massgrave.dev/img/logo_github.png (GitHub)
[1.6]: https://massgrave.dev/img/logo_azuredevops.png (AzureDevOps)
[1.7]: https://massgrave.dev/img/logo_gitea.png (自建 Git)

[1]: https://discord.gg/j2yFsV5ZVC
[2]: https://www.reddit.com/r/MAS_Activator
[3]: https://bsky.app/profile/massgrave.dev
[4]: https://twitter.com/massgravel
[5]: https://github.com/massgravel/Microsoft-Activation-Scripts
[6]: https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts
[7]: https://git.activated.win/Microsoft-Activation-Scripts

---

最新版本：3.12  
发布日期：2026-07-04
