# OpenAI Codex Timeline

A source-backed timeline of OpenAI Codex, from the original 2021 coding model to the modern CLI, cloud agent, apps, models, and integrations.

**Last verified:** September 30, 2026

**Latest major update:** September 29, 2026

**Published article:** [Codex Timeline: Release Dates, Versions, and Major Updates](https://www.scriptbyai.com/codex-timeline/)

## About this repository

OpenAI has used the Codex name for two related but distinct products. The first was a GPT-3 descendant that translated natural-language instructions into code. OpenAI opened its API private beta in August 2021 and retired the original model family in March 2023.

The name returned in April 2025 with Codex CLI, an open-source coding agent that could inspect repositories, edit files, and run commands in a local terminal. A cloud agent followed in May 2025. Later releases connected Codex with IDEs, code review, desktop and mobile apps, remote hosts, browser tools, automation, and specialized models.

This repository records the releases that changed Codex's product identity, capabilities, access, principal interfaces, or model selection. It does not attempt to duplicate every Codex CLI patch or isolated bug fix.

## Latest update

On September 29, 2026, GPT-6.1 Sol launched in Codex, ChatGPT Work, and the API, and Codex CLI 0.159.1 made it the default bundled model. OpenAI also introduced GPT-6 Astra Ultrafast, reusable Codex Cloud environments, a redesigned desktop code review workflow, Codex Security Cloud, and computer use in the Agents API. GPT-6.1 Sol Ultrafast was announced for a later release. Stable CLI versions 0.157.0 through 0.159.0 added full-screen session defaults, MCP authentication options, and optional immediate steering. This timeline excludes alpha builds and releases limited to fixes.

## Timeline at a glance

| Date | Event | What changed |
|---|---|---|
| September 29, 2026 | GPT-6.1 Sol in Codex and API | The upgraded Sol model launched in Codex, ChatGPT Work, and the API; CLI 0.159.1 made it the default bundled model. |
| September 29, 2026 | GPT-6 Astra Ultrafast | A faster Astra service tier launched in Codex for Pro 500 and Enterprise and in the API; GPT-6.1 Sol Ultrafast was announced for later. |
| September 29, 2026 | Codex Cloud environments | Reusable cloud development environments launched with repository setup, shared configuration, and separate task state. |
| September 29, 2026 | Code Review and Codex Security Cloud | The desktop app gained a redesigned pull-request review workflow, while Security Cloud added hosted GitHub repository scans and monitoring. |
| September 29, 2026 | Agents API computer use | The Agents API added computer use for developer-built agents. |
| September 29, 2026 | Codex CLI 0.159.1 | GPT-6.1 Sol became the default bundled model and entered the Amazon Bedrock catalogs. |
| September 29, 2026 | Codex CLI 0.159.0 | An opt-in setting enabled immediate steering during responses or long code-mode calls; session and transcript controls improved. |
| September 28, 2026 | Codex CLI 0.158.0 | Full-screen copying improved, MCP OAuth client secrets gained support, and direct executor connections could use bearer tokens. |
| September 25, 2026 | Codex CLI 0.157.0 | Full-screen transcripts and eligible background-server startup became defaults; remote import and cross-app conversation forks arrived. |
| September 22, 2026 | GPT-6 Sol and Luna in Codex and API | Two lower-cost GPT-6 models joined Codex and the API for complex agent work and focused, high-volume tasks. |
| September 22, 2026 | Codex CLI 0.156.0 | Voice became default; the release added a searchable full-screen UI, usage analytics, and worktree sessions enabled by default. |
| September 17, 2026 | Codex CLI 0.155.0 | Experimental voice, task controls, Touch ID MCP verification, and configurable daemon updates arrived. |
| September 10, 2026 | Agents API public beta | Developers gained API access to the managed Codex harness, durable sessions, context compaction, MCP, and parallel subagents. |
| September 10, 2026 | Data plugin in Codex | The Data plugin entered ChatGPT Work and Codex for connected business-data analysis, dashboards, and reports. |
| September 9, 2026 | GPT-6 Astra in Codex and API | Astra entered the Codex model picker and API; CLI 0.154.0 also added managed worktrees and inline asynchronous questions. |
| September 3, 2026 | Codex CLI 0.153.1 | GPT-6-Astra could be configured through the API without changing the default model or appearing in the model picker. |
| September 3, 2026 | Codex CLI 0.153.0 | Vim draft undo/redo, remote marketplace plugin management, optional automatic recaps, richer TUI history, and earlier usage warnings arrived. |
| September 1, 2026 | Codex CLI 0.152.0 | Vim search, actionable rate-limit banners, credential-refresh progress, package-style MCP names, per-tool output limits, and longer shell-command timeouts arrived. |
| August 26, 2026 | Codex CLI 0.150.0 | Task mentions, response-copy choices, descriptive titles, clickable terminal links, interrupt hooks, and permission-mode shortcuts arrived. |
| August 20, 2026 | ChatGPT desktop | Apple Messages, Site co-editing, editable hosted Site URLs, and Computer History expansion arrived in the ChatGPT desktop workflow. |
| August 20, 2026 | Codex CLI 0.149.0 | An interactive `codex agents` dashboard, queued messages, working-directory commands, and richer `codex doctor` diagnostics arrived. |
| August 18, 2026 | Codex CLI 0.148.0 | Markdown export, session fork/archive/restore, thread cost estimates, an Amazon Bedrock provider, and async hooks/MCP tools arrived. |
| August 13, 2026 | ChatGPT desktop | ChatGPT can now remember your activity across the apps and websites on your computer with Computer History. |
| August 11, 2026 | ChatGPT desktop | You can now keep your work from other agents in sync with ChatGPT Work and Codex. |
| August 11, 2026 | ChatGPT desktop | You can now use ChatGPT, ChatGPT Work, and Codex on supported Linux systems with projects and browser workflows. |
| August 7, 2026 | Codex CLI 0.147.0 | Portable Agent Plugins, catalog search, persistent conversation sections, paginated transcript browsing, and Cursor/Claude import synchronization arrived. |
| July 29, 2026 | Codex CLI 0.146.0 | Named and pinned sessions, Agent Plugins publishing and marketplaces, paginated forks, remote Code Mode, and standalone web search expanded the CLI. |
| July 28, 2026 | Codex Security | OpenAI open-sourced the Codex Security CLI and SDK for finding, validating, and fixing security vulnerabilities in code. |
| July 23, 2026 | Voice | Users can control their computer and direct multiple agents in ChatGPT Work or Codex with voice. |
| July 23, 2026 | Projects | Local projects can include related code, docs, and reference files from multiple folders while one primary folder remains the Git root. |
| July 21, 2026 | Codex CLI 0.145.0 | Paginated history, Cursor and Claude Code imports, Amazon Bedrock login, audio inputs and outputs, multi-agent V2, and inline visualization links arrived. |
| July 9, 2026 | ChatGPT desktop integration | Codex joined the ChatGPT desktop app on macOS and Windows. |
| July 9, 2026 | GPT-5.6 | Sol, Terra, and Luna became available in Codex. |
| July 9, 2026 | Codex CLI 0.144.0 | A `writes` approval mode, interactive MCP authentication, hosted login support, and usage-credit details arrived. |
| July 8, 2026 | Codex CLI 0.143.0 | Remote plugins became the default, system proxy support expanded, remote-control pairing arrived, and Bedrock gained GPT-5.6 model routing. |
| June 25, 2026 | Codex Remote GA | Paired mobile devices could control work on Mac and Windows hosts. |
| June 22, 2026 | Codex CLI 0.142.0 | Usage credits, plugin recommendations, token budgets, multi-agent controls, indexed web search, and scheduled time reminders arrived. |
| June 18, 2026 | Codex CLI 0.141.0 | Encrypted remote executor relays, cross-platform remote execution, selected plugin MCP servers, and child-thread and import APIs arrived. |
| June 2, 2026 | Sites and role-specific plugins | Codex added hosted Sites and plugin collections for specific professions. |
| May 26, 2026 | Model deprecations | GPT-5.3-Codex and GPT-5.2 left the ChatGPT-authenticated model picker. |
| May 14, 2026 | Mobile preview and Remote SSH GA | Codex entered ChatGPT mobile, and Remote SSH reached general availability. |
| May 7, 2026 | Codex for Chrome | A browser extension added controlled access to signed-in tabs. |
| April 23, 2026 | GPT-5.5 and browser use | A new recommended model and active in-app browser operation arrived. |
| April 16, 2026 | Expanded app workspace | Projectless chats, computer use, Automations, artifact previews, and memories expanded the app. |
| March 25, 2026 | Plugins | Installable bundles combined Skills, app integrations, and MCP configuration. |
| March 6, 2026 | Codex Security preview | Aardvark became a repository-aware application security agent in Codex. |
| March 5, 2026 | GPT-5.4 | A general-purpose frontier model with native computer use entered Codex. |
| March 4, 2026 | Windows app | The native app arrived with PowerShell and Windows sandbox support. |
| February 12, 2026 | GPT-5.3-Codex-Spark preview | A low-latency model targeted real-time coding. |
| February 5, 2026 | GPT-5.3-Codex | The model added stronger general reasoning and mid-turn steering. |
| February 2, 2026 | Codex app for macOS | A desktop interface organized parallel agents, worktrees, and reviews. |
| January 14, 2026 | GPT-5.2-Codex API | API-key workflows gained access to the model. |
| December 19, 2025 | Agent Skills | Reusable instruction packages arrived in the CLI and IDE extension. |
| December 18, 2025 | GPT-5.2-Codex | Long-horizon, Windows, vision, and security performance improved. |
| November 19, 2025 | GPT-5.1-Codex-Max | Multi-context compaction supported longer agent tasks. |
| November 13, 2025 | GPT-5.1-Codex models | Standard and Mini variants expanded the model lineup. |
| October 6, 2025 | General availability | Codex reached GA with Slack, SDK, administration, and GitHub tools. |
| September 15, 2025 | GPT-5-Codex and IDE extension | Codex gained a coding model, rebuilt CLI, and editor interface. |
| June 3, 2025 | Plus expansion | ChatGPT Plus access and task internet controls arrived. |
| May 16, 2025 | Cloud research preview | Codex began running delegated engineering tasks in isolated environments. |
| April 16, 2025 | Codex CLI | OpenAI released its open-source local coding agent. |
| March 2023 | Original models discontinued | The 2021 Codex API model family was retired. |
| August 10, 2021 | OpenAI Codex private beta | The natural-language-to-code model entered API testing. |

## Milestones by era

### 2021 to 2023: the original Codex models

OpenAI introduced Codex on August 10, 2021, as a model that translated natural-language instructions into code. It descended from GPT-3 and supported Python plus more than a dozen other programming languages. GitHub Copilot used Codex as its underlying model during this period.

The original release generated code in response to prompts. It did not independently inspect a repository, edit files, execute commands, or verify a result through an agent loop. OpenAI discontinued these Codex API models in March 2023.

### 2025: Codex returns as an agent

Codex CLI revived the name on April 16, 2025. The terminal agent worked inside a developer's local environment and could examine a project, modify files, run commands, and inspect the results. OpenAI released its implementation at [openai/codex](https://github.com/openai/codex).

The [Codex cloud research preview](https://openai.com/index/introducing-codex/) followed on May 16. Each assigned task ran in an isolated environment prepared with the selected repository. The cloud agent could implement features, answer questions about a codebase, fix bugs, run tests, and prepare changes for review.

The product reached [general availability](https://openai.com/index/codex-now-generally-available/) on October 6. By the end of 2025, Codex included a rebuilt CLI, an IDE extension, cloud tasks, code review, a TypeScript SDK, Slack integration, a GitHub Action, Agent Skills, and several coding-focused GPT-5 models.

### 2026: Codex expands across applications and devices

The dedicated Codex app launched on macOS in February 2026 and Windows in March. It organized parallel threads, worktrees, review tools, terminals, Skills, and Automations in a desktop interface. Later updates added projectless chats, an in-app browser, computer use, artifact previews, memories, plugins, and remote connections.

Mobile access entered preview in May. Codex Remote reached general availability in June and connected authenticated phones with Mac or Windows hosts. Codex also moved into browser work through an in-app browser and the Codex for Chrome extension.

The model line changed quickly during the same period. GPT-5.3-Codex added mid-turn steering, GPT-5.4 brought a mainline general-purpose model into Codex, and GPT-5.6 introduced persistent Sol, Terra, and Luna tiers. GPT-6 Astra entered Codex on September 9; GPT-6 Sol and GPT-6 Luna followed on September 22. GPT-6.1 Sol launched on September 29 and became the default bundled CLI model in version 0.159.1. Codex joined the main ChatGPT desktop app on July 9.

The stable CLI releases from June through September added a second layer of product changes. Versions 0.141.0 and 0.142.0 strengthened encrypted remote execution, usage controls, plugins, token budgets, indexed search, and time reminders. Versions 0.143.0 and 0.144.0 added remote plugins, system proxy support, remote-control pairing, Bedrock routing, safer write approvals, and interactive MCP authentication. Versions 0.145.0 through 0.147.0 added imported work, audio, multi-agent controls, named sessions, portable plugins, searchable history, and paginated forks. Version 0.148.0 added Markdown export, session archive and restore, cost estimates, Bedrock Runtime, and asynchronous hooks. Version 0.149.0 added the `codex agents` dashboard, queued messages, working-directory commands, and diagnostic checks. Versions 0.150.0 and 0.152.0 added task references, interrupt hooks, usage feedback, package-style MCP names, per-tool output limits, and shell controls. Versions 0.153.0 and 0.153.1 improved draft recovery, remote plugin management, transcript history, reconnects, context management, and GPT-6 Astra API configuration. Version 0.154.0 added Astra to the model picker and introduced managed worktrees and inline asynchronous questions. Version 0.155.0 added experimental voice, task controls, local Touch ID verification for MCP, and configurable daemon updates. Version 0.156.0 made voice conversations default and added the full-screen TUI, usage analytics, worktree sessions enabled by default, themes, and rendered Mermaid diagrams and equations. Version 0.157.0 made full-screen transcripts and eligible background-server startup defaults. Version 0.158.0 added MCP OAuth client-secret support and bearer-token executor connections. Version 0.159.0 added optional immediate steering during responses and long code-mode calls.

August desktop updates added supported Linux access, Computer History, Apple Messages, Site co-editing, editable hosted Site URLs, and Computer History availability in Europe. DevDay in September introduced reusable Codex Cloud environments, desktop code review changes, Codex Security Cloud, computer use in the Agents API, and GPT-6 Astra Ultrafast for eligible plans and API users. These changes connected Codex more closely with the operating system and the wider ChatGPT work surface.

## Codex product surfaces

| Surface | Role |
|---|---|
| Codex CLI | Runs local agent sessions in a terminal under configured sandbox and approval rules. |
| IDE extension | Adds repository context, review, local work, and cloud handoff to VS Code and compatible editors. |
| Codex Cloud | Runs delegated tasks in reusable OpenAI-managed development environments. |
| ChatGPT desktop app | Manages Codex projects, threads, worktrees, review, terminals, Automations, plugins, browser tools, and computer use. |
| ChatGPT mobile app | Starts, follows, steers, and approves work on connected hosts. |
| SDK and integrations | Connect the Codex agent with CI, Slack, GitHub, hooks, and custom internal tools. |
| Codex Security | Investigates repository vulnerabilities and proposes patches through a separate research-preview workflow. |

## Sources

The timeline gives priority to OpenAI announcements, OpenAI developer documentation, and the official Codex repository. The principal sources are:

- [OpenAI Codex, 2021](https://openai.com/index/openai-codex/)
- [Introducing Codex, 2025](https://openai.com/index/introducing-codex/)
- [Codex general availability](https://openai.com/index/codex-now-generally-available/)
- [Introducing the Codex app](https://openai.com/index/introducing-the-codex-app/)
- [Codex CLI 0.157.0](https://github.com/openai/codex/releases/tag/rust-v0.157.0), [0.158.0](https://github.com/openai/codex/releases/tag/rust-v0.158.0), [0.159.0](https://github.com/openai/codex/releases/tag/rust-v0.159.0), and [0.159.1](https://github.com/openai/codex/releases/tag/rust-v0.159.1)
- [Introducing GPT-6.1 Sol](https://openai.com/index/introducing-gpt-6-1-sol/)
- [DevDay 2026 recap](https://openai.com/index/devday-2026-recap/)
- [Codex Cloud documentation](https://learn.chatgpt.com/docs/cloud)
- [Codex changelog](https://developers.openai.com/codex/changelog)
- [OpenAI Codex releases on GitHub](https://github.com/openai/codex/releases)

## Contributing updates

Corrections and new milestone proposals can be submitted through an issue or pull request. A useful contribution includes:

1. the exact event date;
2. the release status;
3. a short explanation of the product change;
4. affected plans, interfaces, or platforms;
5. a link to an official OpenAI source.

Updates should keep the timeline table and milestone summaries consistent. Claims based only on rumors, screenshots without provenance, or third-party summaries are not added as confirmed events.

## Related resources

- [Claude Code Timeline](https://www.scriptbyai.com/claude-code-timeline/)
- [OpenAI Codex Commands Cheat Sheet](https://www.scriptbyai.com/codex-commands-cheat-sheet/)
- [OpenAI and ChatGPT Timeline](https://www.scriptbyai.com/timeline-of-chatgpt/)
- [Best Agent Skills](https://www.scriptbyai.com/best-agent-skills/)
- [Best CLI AI Coding Agents](https://www.scriptbyai.com/best-cli-ai-coding-agents/)

## Disclaimer

This is an independent reference project maintained by [ScriptByAI](https://www.scriptbyai.com/). It is not affiliated with or endorsed by OpenAI. OpenAI, ChatGPT, GPT, and Codex are trademarks of their respective owner.
