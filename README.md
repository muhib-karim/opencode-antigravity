

# ☕ OpenCode + Antigravity Integration

### Connect OpenCode to an Antigravity-managed provider



[![Live Website](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-e8d5b7?style=for-the-badge)](https://opencode-antigravity.vercel.app)
[![Support on Ko-Fi](https://img.shields.io/badge/☕_Support-Ko--Fi-ff5e5b?style=for-the-badge)](https://ko-fi.com/ai_dev_2024)



[![Version](https://img.shields.io/badge/Version-1.2.0-1a1614?style=flat-square)](CHANGELOG.md)
[![License](https://img.shields.io/badge/License-MIT-1a1614?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/muhib-karim/opencode-antigravity?style=flat-square&color=e8d5b7)](https://github.com/muhib-karim/opencode-antigravity)
[![ZAI Community](https://img.shields.io/badge/Part%20of-ZAI%20Start--up%20Community-8b5cf6?style=flat-square)](https://startup.z.ai/)



---



## ✨ Why This Integration?



| Feature | Description |
|:---:|:---|
| **Account routing** | Integrates with the configured Antigravity account pool. Provider quotas and rate limits still apply. |
| 📋 **Clipboard Image Paste** | Press `Ctrl+V` to paste screenshots directly into your AI prompts |
| **Local proxy connection** | Connects OpenCode to a local proxy on port 8888. Remote provider latency still applies. |
| **Data handling** | The proxy runs locally. Prompts and code sent for inference may be forwarded to the configured remote provider. Review that provider's data policy. |
| 🆓 **Free Models Included** | OpenCode's built-in free models remain available when supported by the installed OpenCode version |

---

## Installation

Inspect the installer before running it. Use elevated PowerShell only when an installation step requires it:

```powershell
Invoke-WebRequest https://raw.githubusercontent.com/muhib-karim/opencode-antigravity/main/release/install.ps1 -OutFile install.ps1
# Review install.ps1 before running it.
.\install.ps1
```

Clone and inspect the local installer instead of piping downloaded code directly into execution:

```bash
git clone https://github.com/muhib-karim/opencode-antigravity.git
cd opencode-antigravity
./release/install.ps1
```

Then **restart OpenCode** and select the Antigravity provider.

---

## 📋 Clipboard Image Paste (Windows Fix)

OpenCode v1.1.47+ supports clipboard image paste, but **Windows Terminal intercepts Ctrl+V** by default.

### Quick Fix:

1. Open **Windows Terminal Settings** (`Ctrl+,`)
2. Go to **Actions** → Find **Paste** (bound to `Ctrl+V`)
3. Change it to `Ctrl+Shift+V`
4. **Restart terminal** and run `opencode`
5. Now **Ctrl+V** will paste images!

> **Tip**: After this change, use `Ctrl+Shift+V` for regular text paste in terminal.

---

## 📸 Demo



**Visit the live demo to see the integration in action:**

[![Website Screenshot](https://img.shields.io/badge/🖼️_View_Demo-opencode--antigravity.vercel.app-e8d5b7?style=for-the-badge)](https://opencode-antigravity.vercel.app)



---

## ☕ Support the Project

If this integration saves you time and API costs, please consider supporting development:



[![Ko-Fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/ai_dev_2024)



---

## 📜 License

MIT License - see [LICENSE](LICENSE) for details.

---


<sub>Built with ☕ by the community</sub>
