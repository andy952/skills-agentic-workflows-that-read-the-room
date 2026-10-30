# GitHub Info

## Mona's editorial angle

Mona's website focuses on practical GitHub guidance backed by official references from:

- docs.github.com
- github.blog
- github.blog/changelog

## Current homepage themes

- GitHub collaboration basics: repositories, branches, pull requests, and merges.
- GitHub Copilot as an AI coding assistant across the IDE, CLI, and GitHub.
- GitHub Actions as the automation layer behind repository workflows.
- Recent GitHub Blog and Changelog stories worth watching.

---

## Latest updates

### GitHub Universe 2026 highlights

GitHub Universe 2026 introduced a wave of Copilot and platform updates. Here are the most practical ones for developers:

- **Copilot Fusion is generally available** — Instead of picking a model per task, Copilot Fusion automatically routes and orchestrates the best model for each step. No more model-switching overhead. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-11-26-route-and-orchestrate-models-with-github-copilot-fusion))_

- **Copilot Automations: build shared AI workflows for your team** — Teams can now create reusable automations that combine prompts, triggers, and tools. Great for standardizing how your org handles issues, PRs, and releases. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-11-26-build-shared-workflows-for-your-team-with-copilot-automations))_

- **GitHub Copilot app spans multiple repos** — Agent sessions in the Copilot app can now work across several repositories at once, useful for features that touch more than one repo. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-11-26-github-copilot-app-universe-releases))_

- **Copilot included with GitHub Enterprise** — Enterprises can now get Copilot bundled into their GitHub Enterprise license for every user, simplifying procurement. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-11-26-github-enterprise-now-includes-access-to-github-copilot))_

- **Security extension for the Copilot app** — Review and triage code scanning alerts directly inside the GitHub Copilot app (public preview). No need to context-switch to the Security tab. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-11-26-security-extension-for-the-github-copilot-app))_

- **Repository plugin defaults and enterprise plugin controls are GA** — Trusted repos can now install and enable default plugins for every contributor automatically in VS Code, Copilot CLI, and the Copilot app. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-11-28-repository-plugin-defaults-and-enterprise-plugin-controls-generally-available))_

- **Generate and edit images directly in Copilot** — Ask Copilot to create or modify images with natural language; the selected reasoning model calls a dedicated image-generation tool. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-10-26-generate-and-edit-images-directly-in-copilot))_

### Copilot workflow tips

- **Continue a Copilot app session in VS Code** — You can now move an agent session from the GitHub Copilot app into VS Code without losing the conversation, code changes, or working context. _(Source: [GitHub Blog](https://github.blog/ai-and-ml/github-copilot/how-to-continue-a-github-copilot-app-session-in-vs-code/))_

### Platform & API updates

- **Webhook IP ranges in the Meta API** — GitHub now publishes webhook delivery IP ranges in the `hooks` field of the Meta API. If you maintain a static network allowlist for webhooks, update it from `/meta`. _(Source: [GitHub Changelog](https://github.blog/changelog/2026-10-29-webhook-ip-ranges-added-to-the-meta-api))_

### Octoverse 2026

GitHub's annual Octoverse report shows a record year: commits and pushes hit new highs as developers increasingly build with AI agents. The growth reached every industry and every kind of builder. _(Source: [GitHub Blog](https://github.blog/news-insights/octoverse/octoverse-commits-pushes-reach-new-highs-in-2026-as-developers-build-with-agents/))_

### Awesome Copilot: ready-to-use workflow templates

The [github/awesome-copilot](https://github.com/github/awesome-copilot/tree/main/workflows) repository collects community workflow templates you can drop into your own repos. Highlights:

| Workflow | What it does |
|---|---|
| **Daily Issues Report** | Runs on a weekday schedule; posts a summary of new, closed, and stale issues as a GitHub issue. |
| **Relevance Check** | Slash command (`/relevance-check`) for maintainers — Copilot reads the issue or PR, checks the current codebase, and posts a relevance verdict with evidence. |
| **OSPO Org Health** | Audits org-wide repository health: stale repos, contributor activity, and compliance signals. |
| **OSPO Release Compliance Checker** | Validates that releases meet defined compliance criteria before they ship. |
| **Weekly Comment Sync** | Summarises discussion threads and syncs key decisions across linked items each week. |

_(Source: [Awesome Copilot workflows](https://github.com/github/awesome-copilot/tree/main/workflows))_
