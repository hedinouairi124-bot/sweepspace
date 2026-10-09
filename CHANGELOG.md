# Changelog

## 0.3.0-beta.2 (Sweepspace Pro beta)

Fixes for the first Pro beta, and the crew closer to its preview film. Pro is still free for everyone during the beta. If you have beta.1, install this over it.

**Fixed**
- Warden no longer blocks harmless text as a "secret": the words "key" or "pem" in a change story, a search or a commit message stalled the crew, waiting for Allow once. Real key files (`server.key`, `.npmrc`, `id_rsa`) are still protected.
- The beta ignores a trial left over from an earlier build, so the crew isn't held to one project.
- The live map picks up every new step as it happens; it no longer lags behind the feed.
- The timeline starts with Scout (the new-branch line was counted as Forge's turn).
- The Crew view stays light under a busy feed: no more long pauses, steady memory.
- `crew trust` says it worked instead of "Sweepspace closed".

**New**
- Change story: each group opens its own lines from the crew's branch.
- A gold Run with crew on every To do card, and Ctrl+Shift+R on the card you're on.
- Your call by keyboard: M (asks first), S to send back with a note, T to take over.
- A run that ended early shows the last real test result instead of empty rings.
- Desktop notifications when the crew needs you: a plan to approve, a verdict, a block, the cap, or a failure.
- Ledger's estimate follows measured runs: about 100k–380k tokens before the brief (it was 150k–450k).

**Measured** (three tasks on a small sample project, every run passing its own type check and tests): the crew used the same tokens as one top-model agent (386k against 384k), cost about 17% less at Claude API prices because only Forge gets the top model, reviewed every change, and took about 2.7 times longer.

**Know before you install**
- A pre-release: it installs over 0.2.1 or beta.1 and keeps your projects and settings. It doesn't update itself to later betas yet; get them from https://sweepspace.pages.dev/pro/.
- The installer is not code-signed, so Windows SmartScreen may warn. Check the hash first.


## 0.3.0-beta.1 (Sweepspace Pro beta)

The first Pro beta. **Pro is free for everyone while it's in beta**: no key, no trial, no sign-up, and the beta sends nothing to Sweepspace. Please report anything that breaks: https://github.com/hedinouairi124-bot/sweepspace/issues

**Pro: the crew**
- Hand a Board task to four bots: Scout researches (read only), Forge builds on its own branch, Warden reviews in a fresh session and blocks risky commands, Ledger keeps the budget with plain rules.
- Runs headless on Claude Code or OpenCode, including OpenCode's free models.
- Crew view: a live map of what each bot read and edited, a Done-when checklist ticked from real test results, a budget with a cap, and Whisper to send a note to the working bot.
- Time travel: scrub the timeline, see what each bot saw, rewind to a checkpoint and branch from there.
- `crew` command: run and answer the crew from any terminal.

**Free for everyone**
- Delegation: Claude Code (and any MCP agent) can hand easy and medium tasks to OpenCode's free models. Each job runs on its own branch with the crew's safety rules, shows as a helper pane next to the agent, and comes back with a diff and checks for the agent to merge, revise or discard. Needs OpenCode installed.
- Map: Go, Java, C#, C/C++, PHP, Ruby, Vue, Svelte and Astro.
- MCP: search ranks code by what it does and across naming styles; `refs` counts only real uses; `impact` says what it doesn't cover; answers carry when they were indexed; re-indexing only when files change.
- Code: search in files, go to definition and find references.
- Changes: push, pull, fetch and pull requests.
- Checks: mypy, Ruff and ESLint when the project sets them up.
- Terminals: WSL distros as shells, find in terminal output, a recent projects menu. Worktrees can run a setup command before the agent starts.

**Know before you install**
- This is a pre-release. It installs over 0.2.1 and keeps your projects and settings. It won't update itself to later betas yet; get them from https://sweepspace.pages.dev/pro/.
- To go back to the stable version, install 0.2.1 from the latest release.
- The installer is not code-signed, so Windows SmartScreen may warn. Check the hash first.


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
