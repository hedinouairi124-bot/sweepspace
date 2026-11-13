# Changelog

## 0.3.0-beta.7 (Sweepspace Pro beta)

A new look, and a crew that spends far fewer tokens. Pro is still free for everyone during the beta. Install over any earlier version; your projects, bots and settings stay.

**A calmer, flatter design**
- Navigation moved to a sidebar on the left, grouped into Work, Code and Project, with your running agents listed under Agents.
- One icon set across the app, and each agent shows its own logo: Claude Code, Codex, Gemini CLI, Antigravity, Kimi and OpenCode.
- Obsidian Glass is now flat and dark, with colour only where it means something. The glow, the gradients and the shouting capital labels are gone.
- Quieter screens: Savings folds its guide and tools away, the map panel and team chat open only when you ask, and empty screens say what to do in one line.

**A leaner crew**
- Each crew bot gets only the tools its job needs and its own short instructions. The fixed cost of every turn dropped from about 13-15k tokens to 4.5-8k.
- Light runs (new): for a one-sentence task, Auto skips Scout, and Warden only reviews a change bigger than 60 lines. The project's own tests and type checker are the checks.
- On our three-task benchmark, all passing: the full crew used 41% fewer tokens than beta 6 and finished about twice as fast. Light runs used 66% fewer.
- The budget cap now follows the estimate for the run you picked, light or full.

**Bots**
- Starter tasks for every bot in the catalog, so a new bot has something useful to do right away.
- Bots plan first on bigger jobs and say clearly when something failed instead of going quiet.
- Bots and Crew load the first time you open them, so the app starts faster.

## 0.3.0-beta.6 (Sweepspace Pro beta)

Bots that remember you, learn skills, run on a schedule and work together. Pro is still free for everyone during the beta. Install over any earlier version; your projects, bots and settings stay.

**A new Bots view**
- Laid out like a messenger: pinned bots on top, sections you name, channels, hidden bots, search, unread dots and each bot's last message.
- Right-click a bot to pin it, move it to a section, mark it unread, make it your main bot, edit it, duplicate it, share it as a template, copy its conversation ID, set its notifications, hide it or delete it.
- A details panel next to the conversation: its screen, what it's for, its routines, its memory, skills, shared files and everything it did.

**Memory**
- Two notebooks: what every bot knows about you, and what only this bot knows. Bots save notes on their own (or say "remember…"), and you can edit or delete any note.
- A new bot says hello and asks a few questions about you.

**Skills**
- A shared library of recipes every bot can follow. Type / in a message to use one. Bots save new skills and update them when you give feedback on the result.
- Bring in your own Claude Code skills from the library.
- Teach by showing (new): do a task once in an Edge window while it records your steps, and the bot turns the recording into a skill.

**Routines**
- Every few minutes, at a time on the days you pick, or when a webhook on this PC is called. A routine can have several triggers.
- Run now, and a run history; click a run to jump to it in the conversation.
- Ask a bot "every weekday at 9, …" and it proposes the routine; it's only saved after you approve it.
- Routines run while Sweepspace is open. One that comes due while its bot is busy is skipped and noted.

**Working together**
- Every bot knows its teammates and can hand work to one. Your main bot (★) sends each request to the right teammate.
- Channels: group chats where bots answer in turn and @mention each other.
- Reply to a specific message, @mention a bot, and see notices when a bot saves a memory, a skill or a routine.

**Drafts**
- Before an email, a message or a post goes out in your name, you get a card to edit, then Send or Discard. The send you approved goes through without asking twice.

**Plugins and templates**
- Plugins shows your apps (your MCP servers in Claude Code) and which bots may use each. Add Notion, Linear, GitHub and others in one click, then sign in once in Claude Code with /mcp.
- Share a bot as a template file, and import one after a look at its instructions, memories, skills and routines.

**OpenCode models stay current**
- OpenCode retired the free models bots used by default. Bots now use "Best free model": the best free model OpenCode offers that day. The list refreshes by itself every few hours, or with Refresh in the model menu. A bot whose model was retired moves to a new one and says so.

**Also**
- This week's token use in the sidebar, desktop notifications per bot, and a shared team folder with context/ and projects/.
- Fixed: editing the CEO in the bot form took away its right to hire and assign.

**Know before you install**
- A pre-release: it installs over 0.2.1 or any earlier beta. Later betas are on https://sweepspace.pages.dev/pro/.
- Newest and least tried: teach by showing, and adding apps from Plugins. Tell us how they go: https://github.com/hedinouairi124-bot/sweepspace/issues
- The installer isn't code-signed, so Windows SmartScreen may warn (More info, then Run anyway). Check the hash first.

SHA-256 of the installer: `deebbe75403edcc3fe70cd9c55f4d58c08094169df4b24a01a1e30d695b14f8e`

## 0.3.0-beta.5 (Sweepspace Pro beta)

Bots can now do real work on your PC. Pro is still free for everyone during the beta. Install over any earlier version; your projects and settings stay.

**Bots that work on your PC**
- Every bot has a new "Where it works" choice: This PC (the new default), its own computer (Docker), or read only.
- On this PC a bot runs commands and edits files in your project like an agent in a terminal. Its browser is an Edge window of its own that keeps its logins; your own Edge profile is never touched.
- It asks before anything risky: uploads, deleting folders, pushing, reading keys or `.env` files, files outside the project, changing its own rules or git hooks, and web addresses stuffed with data. The card shows the whole command.
- Claude Code bots can use your own MCP servers from your Claude Code settings. Lookups run freely, and a tool that changes something asks first.
- OpenCode bots get the same powers on free models, and a busy model is swapped for another free one by itself. OpenCode can't stop and ask mid-run, so a risky step is refused and the bot tells you what it wanted to do.
- No Docker? Bots you hire work on your PC from the start. A bot set up for its own computer works here while Docker is off, and asks before every command.
- The first browser job fetches Node.js if your PC doesn't have it.

**Obsidian Glass**
- A new look for every view, lit by your agents as they work. Paper is still in Settings.

**Faster and steadier**
- Terminals, the map and MCP calls respond faster, and the crew counts changed lines without waiting on git.
- Team chat no longer loses a message when two agents post at once, and agents still running in a project you left stay out of the new one's room.
- The crew retries only on real busy-model errors, and keeps a Pause or Raise cap you press while it waits.
- A terminal's last lines now arrive before it shows as exited.

**New guide**
- https://sweepspace.pages.dev/guide/ covers setup and the harder jobs: a bot on your PC, browsers that stay logged in, a CEO with a team, free models only, and your own rules.

**Know before you install**
- A pre-release: it installs over 0.2.1 or an earlier beta. Later betas are on https://sweepspace.pages.dev/pro/.
- The installer isn't code-signed, so Windows SmartScreen may warn. Check the hash first.




## 0.3.0-beta.4 (Sweepspace Pro beta)

Works out of the box, free or paid. Pro is still free for everyone during the beta. If you have an earlier beta, install this over it.

**Nothing to set up by hand**
- Getting ready: on first start Sweepspace fetches what's missing by itself (Git and OpenCode) from their official sources, checks each download against its published checksum, and shows its progress. Settings › Getting ready lists what's there.
- Any agent in one click: Start an agent › Add more agents › Install. Claude Code, Codex, Gemini CLI, Antigravity, Kimi and Aider install by themselves (Node.js or uv are fetched first if your PC has neither) and start when they're ready.
- Anything missing says so with an Install button next to it, in the crew's check and in a bot's conversation.
- Fresh PCs: agents get a Git author when none is set, so commits never fail.

**Free with OpenCode, no subscription**
- Without Claude Code, every bot, the CEO's hires and the crew run on OpenCode's free models.
- Docker is optional: without it bots work on your PC (they read the project and the web). With Docker running they also get a computer of their own.

**The Sweepspace MCP connects itself**
- Every installed agent gets Sweepspace's map tools on start, OpenCode included, and a registration left by an old install is repaired. An agent you switch off in Savings stays off.

**Bots**
- Switch a bot's brain from its conversation: Claude Code (Sonnet, Opus, Haiku) or OpenCode and its free models.
- The CEO's team works as one: each bot gets the goal, what its teammates are doing and what the team found so far; reports reach the CEO by themselves; new wait_for_team.
- Fixes from real runs: a CEO waiting on the crew is no longer stopped as idle; a crew paused at its token cap is raised once instead of read as done; testers are told where the crew's branch is in their computer; bots may read the project map and save documents in `.sweepspace/team`.
- Replies show headings, lists, tables and code. The bot editor scrolls on small windows and Save stays visible.

**Smaller screens**
- The project name stays in the top bar, and the crew's badges and map labels no longer overlap.



## 0.3.0-beta.3 (Sweepspace Pro beta)

Bots arrive, and the crew's builder gets a computer of its own. Pro is still free for everyone during the beta. If you have an earlier beta, install this over it.

**New: Bots**
- Coworkers that remember the conversation, work on a computer of their own, and ask you before anything that sends, posts, pays or touches a secret. Open **Bots** in the top bar.
- Hire one from the catalog (CI Doctor, App Tester, Dependency Keeper, Docs Researcher, Issue Triage, Web Helper) or write your own. Each bot is a small Markdown file: in `.sweepspace/bots/` for a project (shared through git), or yours for every project.
- Its own computer: a Linux desktop in Docker that keeps its browser logins. Watch it live in "Its screen", take control any time, and hand it back.
- The browser reads pages as text with named elements (Playwright), so bots click what the page calls "Post comment" instead of guessing from screenshots, for far fewer tokens.
- Asks first: sending, posting and uploading wait for your OK in a card with Allow once, Always allow and Deny. Passwords, payments, security settings, pushing to the main branch and secret files always ask, whatever the rules say. Rules live in `.sweepspace/rules.yaml`.
- "What it did": every action with the rule that decided it. Budgets per run and per day; near the end of a run the bot is told to wrap up instead of being cut off.
- Runs on Claude Code, or on OpenCode's free models inside the bot's computer. A bot whose free model is busy retries, then tries its backup model.
- If Sweepspace closes during a run, the bot says so, and Continue picks it up.

**New: agent computers for the crew and terminals**
- "Give Forge its own computer" when you hand a task to the crew: its commands, tests and browser checks run in a Linux desktop, and Ledger checks its work there too.
- "Terminal in its own computer" in the new-terminal menu, with a Desktop button to watch it.

**Know before you install**
- Bots with a computer and agent computers need Docker Desktop (free for personal use). The first computer builds once: about 2.8 GB, a few minutes on a fast connection. About 700 MB of free memory per running computer; at most two run at once.
- A pre-release: it installs over 0.2.1 or an earlier beta and keeps your projects and settings. It doesn't update itself to later betas yet; get them from https://sweepspace.pages.dev/pro/.
- The installer is not code-signed, so Windows SmartScreen may warn. Check the hash first.




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
