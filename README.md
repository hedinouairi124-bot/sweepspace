<div align="center">

<a href="https://sweepspace.pages.dev"><img src="assets/app-icon.svg" width="88" alt="Sweepspace"></a>

# Sweepspace

A desktop workspace for AI coding agents. Run Claude Code, Codex, Gemini and any CLI side by side,<br>
and give every agent a live map of your project so it reads the one function it needs instead of whole files.

[![Download for Windows](https://img.shields.io/badge/Download-Windows%2010%20%26%2011-9ee6c4?style=for-the-badge&labelColor=1c1b18)](https://github.com/hedinouairi124-bot/sweepspace/releases/latest)
[![Website](https://img.shields.io/badge/Website-sweepspace.pages.dev-e6dfcd?style=for-the-badge&labelColor=1c1b18)](https://sweepspace.pages.dev)

[![Latest release](https://img.shields.io/github/v/release/hedinouairi124-bot/sweepspace?include_prereleases&label=release&color=1e6b4f&labelColor=1c1b18)](https://github.com/hedinouairi124-bot/sweepspace/releases)
[![Downloads](https://img.shields.io/github/downloads/hedinouairi124-bot/sweepspace/total?color=1e6b4f&labelColor=1c1b18)](https://github.com/hedinouairi124-bot/sweepspace/releases)
![Platform](https://img.shields.io/badge/platform-Windows%20x64-1e6b4f?labelColor=1c1b18)

<a href="https://sweepspace.pages.dev/"><img src="assets/hero-map.jpg" alt="Sweepspace with the live map of an example project" width="820"></a>

<sub><a href="https://sweepspace.pages.dev">sweepspace.pages.dev</a></sub>

</div>

---

## Why

Coding agents often reopen files they have already read. Sweepspace runs a small local MCP server that your agents connect to in one click, so they can ask for one function or a file outline instead of a whole file.

| One task, 12 steps, Sweepspace's own code | Tokens |
| --- | ---: |
| Opening each file once, in full, plus the compiler's full output | 35,777 |
| **With Sweepspace** | **3,833** |
| | **9.3× fewer** |

Reviewing changes took 14.6× fewer tokens, and type-checking 158× fewer. That's one task on one repo, so yours will differ. The app measures your own under Savings, then Measure.

The tools agents get: `overview` · `search` · `grep` · `refs` · `outline` · `read_symbol` · `read_lines` · `impact` · `context` · `problems` · `check` · `changes`

## Features

<table>
<tr>
<td width="50%" valign="top">

### Run agents side by side
Claude Code, Codex, Gemini CLI, OpenCode, Aider, Kimi and any shell, in a grid of real terminals. Each agent can work on its own branch.

</td>
<td width="50%"><img src="assets/s-terminals.jpg" alt="Three agents side by side"></td>
</tr>
<tr>
<td><img src="assets/hero-map.jpg" alt="The live map"></td>
<td valign="top">

### A live map of your project
Every file, import and symbol, coloured by health: broken, at risk, verified. Agents read the map instead of the whole repo.

</td>
</tr>
<tr>
<td valign="top">

### A task board
A board for agent work: queue tasks, run them on separate branches, review and merge.

</td>
<td><img src="assets/s-board.jpg" alt="Task board"></td>
</tr>
<tr>
<td><img src="assets/s-changes.jpg" alt="Changes view"></td>
<td valign="top">

### Review every change
Diffs per agent and per branch, with checkpoints you can roll back to.

</td>
</tr>
<tr>
<td valign="top">

### See what you saved
The Savings screen counts the tokens the map saved, by tool and by day. Press Measure to test your own project.

</td>
<td><img src="assets/s-savings.jpg" alt="The Savings screen"></td>
</tr>
<tr>
<td><img src="assets/s-tidy.jpg" alt="Tidy"></td>
<td valign="top">

### Clean up a project
Finds committed secrets, junk files and duplicates, shows every change first, and one click undoes it.

</td>
</tr>
</table>

## Install

1. Download `Sweepspace_x.y.z_x64-setup.exe` from the [latest release](https://github.com/hedinouairi124-bot/sweepspace/releases/latest), or from [the website](https://sweepspace.pages.dev/#download).
2. Check the file (optional, recommended). In PowerShell, in your Downloads folder:
   ```powershell
   Get-FileHash .\Sweepspace_0.2.1_x64-setup.exe
   ```
   The hash must match `SHA256SUMS.txt` in the release.
3. Run it. It installs for your Windows user and doesn't need admin rights.

> [!NOTE]
> The beta installer isn't code-signed yet, so Windows may not recognise it. Edge may say the file isn't commonly downloaded (choose **Keep**), and SmartScreen may say it protected your PC (choose **More info**, then **Run anyway**). Only do that if the hash matches.

**Price:** free.

**Requirements:** Windows 10 or 11, 64-bit. The agents you want to use (for example Claude Code or Codex) are installed separately and keep their own sign-in.

## Privacy

- Sweepspace runs on your PC. The map, the checks and the machine scan stay local.
- It never stores API keys. Your agents talk to their own providers, as they already do.
- Before it runs a folder's own type checker or tests, Sweepspace asks whether you trust that folder.

## Sweepspace Pro

In beta and free during the beta: a crew that takes a task to a reviewed branch, and bots that work on your PC and ask before risky actions. The planned price after the beta is $8 a month. [Details](https://sweepspace.pages.dev/pro/).

## Who makes this

Made by [Hedi Nouairi](https://github.com/hedinouairi124-bot), a CS engineering student in Tunisia. Bugs and ideas go in [Issues](https://github.com/hedinouairi124-bot/sweepspace/issues).

## Feedback and support

- Found a bug? [Open an issue](https://github.com/hedinouairi124-bot/sweepspace/issues/new/choose).
- Found a security problem? Please report it privately. See [SECURITY.md](SECURITY.md).

---

<div align="center"><sub>© 2026 Sweepspace. All rights reserved. This repository hosts releases and documentation; the source code is not public.</sub></div>
