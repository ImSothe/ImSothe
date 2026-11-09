<div align="center">

# Ángel Baz Monteiro

**Systems technician who builds secure Windows tools in C# / .NET.**<br/>
[Toji](https://github.com/ImSothe/Toji-Windows-Optimizer) (84 reversible tweaks) · [SignedUpdater](https://github.com/ImSothe/SignedUpdater) (signed auto-update) · [Finanzas](https://github.com/ImSothe/Finanzas) (offline PWA).<br/>
Open to: Windows systems and automation, or .NET roles · Spain, remote or relocation.

<img src="https://skillicons.dev/icons?i=cs,dotnet,powershell,js,nodejs,react,threejs,python,git,github&theme=dark" alt="C#, .NET, PowerShell, JavaScript, Node.js, React, Three.js, Python, Git" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ángel%20Baz-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%C3%A1ngel-baz-monteiro-8196a21a9/)
[![Toji](https://img.shields.io/badge/flagship-Toji-8b5cf6)](https://github.com/ImSothe/Toji-Windows-Optimizer)

</div>

---

## 👋 About

Systems & software builder. I like building from the ground up: Windows internals and native APIs on one side, 3D on the web on the other, and automation tying it together. I ship things I actually use: a tuning tool that can undo everything it does, an updater that refuses unsigned binaries, an expense app that works offline.

I work with AI assistance (Claude Code) as a pair programmer: I decide what gets built, how it must behave and how it is verified. Every project links its tests and lists its own limits, so you can check the result instead of taking my word for it.

## ⭐ Featured

<div align="center">
<a href="https://github.com/ImSothe/Toji-Windows-Optimizer"><img src="https://raw.githubusercontent.com/ImSothe/Toji-Windows-Optimizer/main/docs/images/toji-demo.gif" width="720" alt="Toji demo: check three tweaks, Apply, then uncheck them and Apply again to revert" /></a>
<br/><sub>Toji applying three tweaks and reverting them. Registry and backups were verified identical afterwards on a real machine.</sub>
</div>

<table>
<tr>
<td width="33%" valign="top">

### [Toji](https://github.com/ImSothe/Toji-Windows-Optimizer)
**Windows tuning tool, MIT.** 84 tweaks, each stored as data. Backups are written *before* every change and undone **LIFO**,
so overlapping tweaks cannot leave the system wrong (a real bug I found, reproduced and fixed). Signed auto-update,
hardened data folder, calibrated timer resolution.
<br/><sub>WPF · .NET 8 · P/Invoke · **196 tests, 87.2 % line coverage** (non-UI), verified apply/revert on a real PC</sub>

</td>
<td width="33%" valign="top">

### [SignedUpdater](https://github.com/ImSothe/SignedUpdater)
**Safe self-update from GitHub Releases.** ECDSA-signed manifest, streaming SHA-256 check under a size cap, host allow-list,
rollback-safe swap. Written up with its threat model **and its limits**.
<br/><sub>.NET 8 · security · 17 tests · MIT</sub>

</td>
<td width="33%" valign="top">

### [Finanzas](https://github.com/ImSothe/Finanzas) · [live](https://imsothe.github.io/Finanzas/)
**Expense PWA on your own Google Sheet.** Log an expense in 3 seconds, or photograph a receipt and let Gemini itemise it.
Offline queue with idempotent replay, hardened Apps Script backend.
<br/><sub>PWA · Apps Script · Gemini · **136 tests** · MIT</sub>

</td>
</tr>
</table>

## 🛠️ More work

| Project | What it is | Stack · proof |
|---|---|---|
| **[WindowsTimerResolution](https://github.com/ImSothe/WindowsTimerResolution)** | `NtSetTimerResolution` wrapper with explicit release and **auto-calibration**. Measured: `Sleep(1)` 15.6 ms → 1.5 ms held, 1.2 ms calibrated. Also documents what did *not* work. | .NET 8 · 13 tests · MIT |
| **[AD Hardware Inventory](https://github.com/ImSothe/AD-Hardware-Inventory)** | Agentless hardware inventory for a Windows domain in one read-only PowerShell script (AD list → parallel WinRM/CIM → CSV). Run in a real 26-computer domain; unreachable machines are reported, not dropped. | PowerShell · MIT |
| **[AI Hoodie Studio](https://github.com/ImSothe/AI-Hoodie-Studio)** | 3D hoodie configurator: place graphics on a 3D garment, pick the technique per piece, export a production dossier PDF. | Next.js 16 · three.js · Fabric.js · prototype · MIT |
| **[Industrial Web Template](https://github.com/ImSothe/Industrial-Web-Template)** | B2B 3D configurator I built on my own as a proposal for a prospective client (no agreement reached; the code is mine), with a hardened reference API (parameterized SQL, XSS/path-traversal defenses, lockout). | Three.js · GSAP · Node |
| **[sheetmetal-geometry](https://github.com/ImSothe/sheetmetal-geometry)** | Pure-JS sheet-metal maths: chained bends, K-factor allowance, flat patterns, boolean-merged cut outlines. | JS · 13 tests · MIT |
| **[Jarvis Project](https://github.com/ImSothe/Jarvis-Project-by-Sothe)** | Voice-driven personal AI assistant for Windows on the open-source [OpenJarvis](https://github.com/open-jarvis/OpenJarvis) framework: native app, local wake-word filter, a tool router that cuts tool-definition tokens per request by up to ~85 %. | Python · Gemini · Apache-2.0 base |

<details>
<summary><b>Products built with a partner (code private, showcase only)</b></summary>

<br/>

| Project | What it is |
|---|---|
| **[APP ENTREGAS](https://github.com/ImSothe/APP-LOGISTICA-showcase)** | Delivery map for several companies: customer flags coloured by order state, courier PWA with routes ordered by real driving time, GPS checkpoints, offline queue, admin panel. Two-person project with [@TenMM2](https://github.com/TenMM2): I designed, specified and tested it (built with Claude Code); TenM built the dependency-free Node.js server and security. 66 tests. |
| **[Plantilla Taller](https://github.com/ImSothe/Plantilla-Taller-showcase)** | White-label platform for auto repair shops: public portal with plate lookup and booking calendar, owner approval of extra work, shop-floor panel with per-task timers and QR labels. Privacy by design, tested Firestore rules, 250 unit tests. Built with [@TenMM2](https://github.com/TenMM2); code private. |

</details>

---

<details>
<summary><b>About the name</b></summary>

<br/>

<div align="center">

<img src="assets/banner.jpg" width="640" alt="Sothe" />

*You're strong... but I don't stop leveling up.*

</div>

</details>

<div align="center">

**Want to talk about any of this? Reach me on [LinkedIn](https://www.linkedin.com/in/%C3%A1ngel-baz-monteiro-8196a21a9/).**

</div>
