# OpenAI Codex Timeline

A source-backed timeline of OpenAI Codex, from the original 2021 coding model to the modern CLI, cloud agent, apps, models, and integrations.

**Last verified:** October 30, 2026

**Latest major update:** October 29, 2026

**Published article:** [Codex Timeline: Release Dates, Versions, and Major Updates](https://www.scriptbyai.com/codex-timeline/)

## About this repository

OpenAI has used the Codex name for two related but distinct products. The first was a GPT-3 descendant that translated natural-language instructions into code. OpenAI opened its API private beta in August 2021 and retired the original model family in March 2023.

The name returned in April 2025 with Codex CLI, an open-source coding agent that could inspect repositories, edit files, and run commands in a local terminal. A cloud agent followed in May 2025. Later releases connected Codex with IDEs, code review, desktop and mobile apps, remote hosts, browser tools, automation, and specialized models.

This repository records the releases that changed Codex's product identity, capabilities, access, principal interfaces, or model selection. It does not attempt to duplicate every Codex CLI patch or isolated bug fix.

## Latest update

Codex CLI 0.166.0 was released on October 29, 2026, with keyboard-driven transcript selection, Terra model catalogs, queued-thread resumption, and network diagnostics. Earlier October releases added prompt presets, Vertex AI support, memory v2 for fresh profiles, and immediate steering by default. GPT-6.1 Terra became available in Codex and Work on October 26. Alpha builds and releases limited to fixes are excluded from the milestone table.

## Timeline at a glance

| Date | Event | What changed |
|---|---|---|
| October 29, 2026 | Codex CLI 0.166.0 | Keyboard-driven transcript selection and search, Terra in bundled, Vertex AI, and Bedrock catalogs, queued-thread resumption, clearer safety-block guidance, and network diagnostics. |
| October 27, 2026 | Codex CLI 0.165.0 | Built-in Google Cloud Vertex AI support, Terra model catalogs, repository filters, mid-conversation reasoning changes, and memory v2 for fresh profiles. Attached thread forks remained experimental. |
| October 26, 2026 | GPT-6.1 Terra becomes available | GPT-6.1 Terra became available in Codex and Work on Plus, Pro, Business, Enterprise, and Edu plans, with image understanding and computer use. Enterprise access depends on administrator controls. |
| October 23, 2026 | Codex CLI 0.164.0 | Ten reusable /presets slots, inline model and permission settings, terminal image previews, enterprise MCP authentication, and remote credential masking. |
| October 15, 2026 | Codex CLI 0.163.0 | Searchable /config preferences, immediate steering by default, configurable leader keys, managed-server restarts, parallel read-only tools, and Daybreak for eligible accounts. |
| October 14, 2026 | GPT-5.5 retires from Codex | GPT-5.5 retired from ChatGPT-authenticated Codex at noon PDT. API-key sessions and the OpenAI API were unaffected. |
| October 11, 2026 | GPT-6.1 Sol default context expands | The default Codex and Work context increased from 272k to 500k tokens, with configuration up to 1M. |
| October 9, 2026 | Composer predictions beta | Personal Pro users aged 18+ gained next-message suggestions in supported local and SSH desktop threads. |
| October 8, 2026 | GPT-6.1 Sol Ultrafast rollout | Ultrafast reached Codex and Work on Pro $500 and eligible Enterprise/Edu plans, plus the Responses API. |
| October 8, 2026 | Faster desktop steering | Follow-up messages could redirect running Codex tasks sooner; settings controlled steering versus queuing. |
| October 8, 2026 | Codex CLI 0.162.0 | Managed-worktree tools, task pinning, transcript copying, provider capability settings, and Code Mode tool search expanded. |
| October 7, 2026 | Codex CLI 0.161.0 | Bedrock gained multi-agent V2 and Ultra reasoning; live MCP login, saved voice-device settings, and explicit Daybreak opt-in arrived. |
| October 7, 2026 | Codex task links on iOS | ChatGPT for iOS 1.2026.272 added direct opening of Codex task links and a clearer approval picker. |
| October 6, 2026 | Auto-review becomes free with ChatGPT sign-in | Automatic approval reviews stopped consuming plan usage; users could select Approve for me. |
| October 5, 2026 | GPT-6 default-speed improvement | GPT-6 Astra and GPT-6.1 Sol received an approximately 50% default-speed improvement through ChatGPT subscriptions. |
| October 2, 2026 | Codex task and usage widgets on iOS | Home Screen widgets showed recent host tasks; Home Screen and Lock Screen widgets tracked usage and reset times. |
| October 1, 2026 | Codex CLI 0.160.0 | Older-task browsing, Linux transcript selection, projectless session defaults, and opt-in approval-review context improved. |
| October 1, 2026 | GPT-5.3-Codex API deprecation announced | API removal was scheduled for April 1, 2027, with GPT-6 Sol as the recommended replacement. |
| September 30, 2026 | Codex CLI 0.159.3 | Eligible local sessions with ChatGPT sign-in gained optional account-security setup reminders. |
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
| September 14, 2026 | GPT-5.3-Codex-Spark discontinued | The Spark research preview ended in the desktop app, CLI, and IDE extension. |
| September 14, 2026 | GPT-5.5 retirement announced | Retirement from ChatGPT, Work, and Codex was scheduled for October 14; API access was excluded. |
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

### September 2026: model retirement notices

September 14, 2026: GPT-5.3-Codex-Spark was deprecated and its research preview became unavailable in the ChatGPT desktop app, Codex CLI, and IDE extension. Saved configurations and scripts that selected gpt-5.3-codex-spark needed a supported replacement.

September 14, 2026: OpenAI announced that GPT-5.5 would retire from ChatGPT, ChatGPT Work, and Codex on October 14, 2026, across consumer, Business, Enterprise, and Edu plans. The OpenAI API was excluded. The Codex retirement took effect on October 14 at noon PDT for ChatGPT-authenticated sessions; API-key sessions were unaffected.

### September 30 to October 2026: speed, permissions, and longer context

**September 30, 2026 — Codex CLI 0.159.3.** Codex CLI 0.159.3 added optional reminders to complete account-security setup in eligible local sessions signed in with ChatGPT.

**October 1, 2026 — Codex CLI 0.160.0.** Codex CLI 0.160.0 added a keyboard-accessible Show more action for older tasks in the agent command center. Supported local Linux X11 terminals gained full-screen transcript selection and middle-click paste. Sessions could start outside a project with workspace defaults when policy allowed, and resumed sessions restored saved permissions. Opt-in Guardian review capabilities could retrieve earlier user instructions and include context from agent handoffs. The release also improved queued-message recovery after reconnects, Windows sandbox behavior, plugin-loading efficiency, and local log storage.

**October 1, 2026 — GPT-5.3-Codex API deprecation announced.** OpenAI deprecated `gpt-5.3-codex` in the API and scheduled removal for April 1, 2027, with six months of notice. The recommended replacement was `gpt-6-sol`. This API deprecation was separate from the model's earlier removal from the ChatGPT-authenticated Codex model picker; API access remains scheduled to end on April 1, 2027.

**October 2, 2026 — Codex task and usage widgets on iOS.** ChatGPT for iOS 1.2026.267 added Home Screen widgets for recent tasks on selected computers. Home Screen and Lock Screen widgets could display remaining usage and reset times. The update also added an option to keep the keyboard open after sending a message.

**October 5, 2026 — GPT-6 default-speed improvement.** OpenAI increased default inference speed for GPT-6 Astra and GPT-6.1 Sol by approximately 50% across its subscription products and partners that use Sign in with ChatGPT. The improvement required no setting change. It applied to the default subscription experience, separately from the Fast and Ultrafast speed tiers.

**October 6, 2026 — Auto-review becomes free with ChatGPT sign-in.** Auto-review became free for users signed in with a ChatGPT account, without consuming their plan usage. Users could select Approve for me in the permissions control below the composer. A separate reviewer agent evaluates eligible approval requests before execution. The main agent retains its configured sandbox, filesystem restrictions, and network limits.

**October 7, 2026 — Codex CLI 0.161.0.** Codex CLI 0.161.0 added multi-agent V2 and Ultra reasoning for compatible Amazon Bedrock models, plus AWS GovCloud regions in Bedrock Mantle. GPT-6.1 Sol remained the default in the bundled and Bedrock catalogs. Users could sign in to an MCP server during an active terminal session with `/mcp login <name>` and save microphone, speaker, and input-channel preferences. Daybreak controls and automatic Cyber routing required explicit opt-in through `--enable cli_daybreak` or `features.cli_daybreak=true`, plus account and model eligibility. The non-interactive CLI and TypeScript SDK also gained per-turn Cyber access-program selection.

**October 7, 2026 — Codex task links on iOS.** ChatGPT for iOS 1.2026.272 added direct opening of Codex task links and inline Page previews. The approval picker received clearer permission choices, while worktree handling and reconnection behavior improved for tasks associated with desktop hosts.

**October 8, 2026 — GPT-6.1 Sol Ultrafast rollout.** GPT-6.1 Sol Ultrafast began rolling out in Codex and ChatGPT Work on Pro $500 and eligible Enterprise and Edu plans. Enterprise access was off by default until workspace owners enabled it. Supported inference-residency regions included the United States and Europe (EEA and Switzerland). Ultrafast consumes usage at higher rates than Standard mode. The Responses API also added Sol Ultrafast for API users, subject to rate limits, through `gpt-6.1-sol` with `service_tier: "ultrafast"`. This release followed the September 29 announcement of the forthcoming tier.

**October 8, 2026 — Faster desktop steering.** OpenAI began rolling out faster steering in the ChatGPT desktop app's Codex experience. Follow-up messages could correct an approach, add information, or redirect a running task sooner. Settings under General and Follow-up behavior controlled whether a message steered the active run or waited for the next one. This desktop rollout followed the CLI's opt-in `instant_interrupt` setting in version 0.159.0.

**October 8, 2026 — Codex CLI 0.162.0.** Codex CLI 0.162.0 added tools to create and list managed Git worktrees from trusted local projects when the worktrees feature was enabled. Supported servers could keep pinned tasks in a shared Pinned group. Transcript controls added block navigation through `/copy`, `Ctrl+Insert` copying, configurable mouse-wheel speed, and clickable URLs across approval prompts and questions. Custom Responses-compatible providers gained configurable live web access and remote compaction capabilities. Code Mode added helpers to return asynchronous results as they completed and an opt-in ranked tool search. Windows releases also gained a signed PowerShell installer.

**October 9, 2026 — Composer predictions beta.** Composer predictions entered beta in the Codex desktop app for personal ChatGPT Pro users aged 18 and older in supported regions. Local and SSH threads with GPT-6 Astra or GPT-6.1 Sol could suggest a complete next message after a response. Pressing Tab accepted the text for review or editing; the user still chose when to send it. Predictions were enabled by default for eligible users and could be disabled through General, Composer, and Show predictions. Generating predictions used no Codex limits or credits during the beta. Sent messages followed normal usage limits and billing.

**October 11, 2026 — GPT-6.1 Sol default context expands.** The default GPT-6.1 Sol context length in Codex and ChatGPT Work increased from 272,000 to 500,000 tokens. Users could still configure it up to one million tokens. Subscription usage carried no additional long-context fee. The change expanded the amount of task history and project material a session could retain before context management became necessary.

**October 14, 2026 — GPT-5.5 retires from Codex.** GPT-5.5 retired from ChatGPT-authenticated Codex at noon PDT. API-key sessions and the OpenAI API were unaffected.

**October 15, 2026 — Codex CLI 0.163.0.** The searchable /config panel applied supported preference changes immediately. Follow-up messages steered active responses by default, and interruptions stopped Code Mode cells and nested tool calls. The release added configurable leader keys, /daemon restarts, and parallel read-only lookups. Daybreak became enabled by default for eligible accounts.

**October 23, 2026 — Codex CLI 0.164.0.** Users could store prompts and slash commands in ten /presets slots and pass inline arguments to /model and /permissions. Compatible Kitty or Sixel terminals could preview images in the transcript. Enterprise MCP authentication and remote credential masking expanded, while disk cleanup removed unused installations and bounded daemon logs.

**October 26, 2026 — GPT-6.1 Terra becomes available.** GPT-6.1 Terra became available in Codex and Work on Plus, Pro, Business, Enterprise, and Edu plans, with image understanding and computer use. Enterprise access depends on administrator controls.

**October 27, 2026 — Codex CLI 0.165.0.** A built-in Vertex AI provider used model_provider = "gcp". Terra joined model catalogs, session navigation gained repository filters, and supported models allowed reasoning changes during conversations by default. Fresh profiles used memory v2 with external-agent memory imports. Attached thread forks in the app-server API remained experimental.

**October 29, 2026 — Codex CLI 0.166.0.** Transcript selection gained keyboard motions, integrated search, and configurable shortcuts. Terra appeared in the bundled, Vertex AI, and Bedrock catalogs. The codex queue --resume command resumed unloaded threads after queueing a message; codex doctor --network-only checked connectivity and WebSockets. The release also clarified safety blocks and preserved permission settings and reasoning-token accounting across resume and fork.

Stable CLI versions 0.159.2, 0.160.1, and 0.162.1 were reviewed but contained fixes only. Version 0.166.0 was the latest stable release verified on October 30.

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

- [Codex CLI 0.159.3](https://github.com/openai/codex/releases/tag/rust-v0.159.3), [0.160.0](https://github.com/openai/codex/releases/tag/rust-v0.160.0), [0.161.0](https://github.com/openai/codex/releases/tag/rust-v0.161.0), [0.162.0](https://github.com/openai/codex/releases/tag/rust-v0.162.0), and [0.162.1](https://github.com/openai/codex/releases/tag/rust-v0.162.1)
- [28 days of shipping tracker](https://community.openai.com/t/28-days-of-shipping-at-openai/1403897)
- [ChatGPT and Codex changelog](https://learn.chatgpt.com/docs/changelog)
- [ChatGPT release notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)
- [Composer predictions](https://help.openai.com/en/articles/20001601-composer-predictions-in-codex)
- [Auto-review](https://learn.chatgpt.com/docs/sandboxing/auto-review) and [speed tiers](https://learn.chatgpt.com/docs/agent-configuration/speed)
- [API deprecations](https://developers.openai.com/api/docs/deprecations) and [API changelog](https://developers.openai.com/api/docs/changelog)

- [Codex CLI 0.163.0](https://github.com/openai/codex/releases/tag/rust-v0.163.0)
- [Codex CLI 0.164.0](https://github.com/openai/codex/releases/tag/rust-v0.164.0)
- [Codex CLI 0.165.0](https://github.com/openai/codex/releases/tag/rust-v0.165.0)
- [Codex CLI 0.166.0](https://github.com/openai/codex/releases/tag/rust-v0.166.0)

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
