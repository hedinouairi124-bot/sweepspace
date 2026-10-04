# Changelog

## 0.2.1

A sturdier, faster People's version. Please report anything that breaks: https://github.com/hedinouairi124-bot/sweepspace/issues

- Night paper: a dark theme (Settings > Appearance, or follow Windows).
- Measure the savings on your own project: Savings > Measure with the real tools.
- Savings switch: long command output from Claude Code is squeezed to what matters, only for commands your own permission rules already allow.
- Antigravity can be connected to the map in one click.
- Terminals: no more doubled lines, agent sessions no longer inherit another tool's settings, and a Sign in button when Claude Code isn't logged in.
- MCP: `impact` and `refs` always use the latest files; outlines say when a file is generated or uses macros; empty answers say what isn't indexed.
- Faster git status, checkpoints and map updates on big projects; a 12k-file project indexes in about a second.
- Safer file handling: paths stay inside the project, tidy-up moves never overwrite a file, and settings are written atomically.
- Clearer error messages, better contrast and keyboard focus.
- Only one Sweepspace window at a time; uninstalling removes the hooks and MCP entries it added.
- Codex token counts no longer double-count resumed sessions.


## 0.2.0 (the People's version)

Free, for everyone who pays for their own tokens.

- New MCP tools: `grep` (text search across code, docs and config) and `refs` (where a function is used).
- Docs and config files can be outlined and read by section; `read_symbol` reads several names at once.
- Re-reading something unchanged in the same session returns a one-line note.
- One-click agent guide in AGENTS.md.
- Savings shows what agents actually used, from Claude Code and Codex logs on this PC, and counts each file once per session.
- Antigravity CLI preset, custom agents, desktop notification when an agent waits.
- Folder trust before a project's own tools run; a sturdier MCP server; the map keeps up with busy folders; error screen and local logs.
- Signed auto-updates from GitHub Releases.
- High-contrast support and a first-run checklist.

## 0.1.0 (beta)

First public beta for Windows 10 and 11.

- Run Claude Code, Codex, Gemini CLI, OpenCode, Aider, Kimi and any shell side by side.
- Live map of your project with per-file health, and ten MCP tools that cut agent token use (9.3× on a measured task).
- Task board with a branch per agent, change review and checkpoints.
- Editor, live preview, machine check and one-click tidy up.
- Reopens your last terminals and editor tabs after a restart.
- Asks before it runs a folder's own type checker or tests.
