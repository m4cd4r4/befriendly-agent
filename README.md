# BeFriendly Remote Agent

> Secure remote support for Windows — built by [BeFriendly Tech Support](https://befriendly.com.au) (Perth, WA)

---

## Download

**[→ Download BeFriendly-RemoteAgent.exe (latest)](https://github.com/m4cd4r4/befriendly-agent/releases/latest/download/BeFriendly-RemoteAgent.exe)**

Windows 10 / 11 · ~4.2 MB · No installation required

---

## How It Works

1. **Download** the .exe above
2. **Right-click → Run as administrator**
3. **Enter the 6-digit code** your technician reads out

Your technician can then run diagnostics and commands on your machine. **You see every action in real-time** — and you can disconnect any time.

Full instructions at [befriendly.com.au/connect](https://befriendly.com.au/connect)

---

## Safety

| Feature | Detail |
|---------|--------|
| **Transparency** | Every command shown to you live |
| **Blocked commands** | `format`, `diskpart`, `cipher /w`, `rd /s /q C:`, `bcdedit`, `bootrec`, and more |
| **Cautious commands** | `reg delete/add`, `netsh`, `sc delete`, `taskkill /f` — logged with warnings |
| **Session expiry** | Sessions close after 2 hours or when you disconnect |
| **No persistence** | Agent doesn't install, doesn't run on startup, leaves no background processes |
| **No data storage** | Command output is relayed to technician in real-time, not stored |

---

## What the Agent Can Do

- Read hardware information (CPU, RAM, disk, GPU, battery, temperature)
- Run PowerShell and CMD commands (with safety checks)
- Read and write files (with automatic backups)
- Analyse Windows Event Viewer logs
- Report system health in real-time

---

## For Technicians

Sessions are created through [Claude Code](https://claude.ai/claude-code) with the `remote-support` MCP server. See [befriendly.com.au](https://befriendly.com.au) for booking.

---

## Release History

See [Releases](https://github.com/m4cd4r4/befriendly-agent/releases) for all versions and changelogs.

---

*Built in Perth, Western Australia. [befriendly.com.au](https://befriendly.com.au)*
