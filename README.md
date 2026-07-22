# OpenAI Codex Timeline

A source-backed timeline of OpenAI Codex, from the original 2021 coding model to the modern CLI, cloud agent, apps, models, and integrations.

**Last verified:** July 22, 2026

**Latest major update:** July 9, 2026

**Published article:** [Codex Timeline: Release Dates, Versions, and Major Updates](https://www.scriptbyai.com/codex-timeline/)

## About this repository

OpenAI has used the Codex name for two related but distinct products. The first was a GPT-3 descendant that translated natural-language instructions into code. OpenAI opened its API private beta in August 2021 and retired the original model family in March 2023.

The name returned in April 2025 with Codex CLI, an open-source coding agent that could inspect repositories, edit files, and run commands in a local terminal. A cloud agent followed in May 2025. Later releases connected Codex with IDEs, code review, desktop and mobile apps, remote hosts, browser tools, automation, and specialized models.

This repository records the releases that changed Codex's product identity, capabilities, access, principal interfaces, or model selection. It does not attempt to duplicate every Codex CLI patch or isolated bug fix.

## Latest update

On July 9, 2026, OpenAI released GPT-5.6 in Codex and integrated Codex into the ChatGPT desktop app for macOS and Windows. GPT-5.6 introduced the Sol, Terra, and Luna model tiers. Existing Codex app projects, settings, and workflows carried into the ChatGPT desktop application. Both changes were full releases, not previews.

## Timeline at a glance

| Date | Event | What changed |
|---|---|---|
| July 9, 2026 | ChatGPT desktop integration | Codex joined the ChatGPT desktop app on macOS and Windows. |
| July 9, 2026 | GPT-5.6 | Sol, Terra, and Luna became available in Codex. |
| June 25, 2026 | Codex Remote GA | Paired mobile devices could control work on Mac and Windows hosts. |
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

The model line changed quickly during the same period. GPT-5.3-Codex added mid-turn steering, GPT-5.4 brought a mainline general-purpose model into Codex, and GPT-5.6 introduced persistent Sol, Terra, and Luna tiers. Codex joined the main ChatGPT desktop app on July 9.

## Codex product surfaces

| Surface | Role |
|---|---|
| Codex CLI | Runs local agent sessions in a terminal under configured sandbox and approval rules. |
| IDE extension | Adds repository context, review, local work, and cloud handoff to VS Code and compatible editors. |
| Codex cloud | Runs delegated tasks and code review in OpenAI-managed environments. |
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
