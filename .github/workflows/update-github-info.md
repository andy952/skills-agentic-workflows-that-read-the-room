---
name: update-github-info
description: Draft website updates for Mona's GitHub Info site from official GitHub sources.
on:
  workflow_dispatch:
  schedule:
    - cron: '17 9 * * *'
safe-outputs:
  create-pull-request:
    title-prefix: "[mona] "
    draft: true
    fallback-as-issue: false
tools:
  edit:
  web-fetch:
network:
  allowed:
    - github.com
    - github.blog
    - awesome-copilot.github.com
engine:
  id: copilot
  copilot-sdk: true
---

# Update Mona's GitHub Info website

Read `notes/mona-notes.md` before making changes.

Use these sources:
- `notes/mona-notes.md`
- GitHub Blog: https://github.blog/latest/
- GitHub Changelog: https://github.blog/changelog/
- Awesome Copilot workflows: https://awesome-copilot.github.com/workflows/

Web fetch the latest GitHub Blog, the GitHub Changelog, and the Awesome Copilot workflows page, then summarize the most relevant updates for Mona's readers.

Update `site/content/github-info.md` with concise, practical updates that reflect both Mona's notes and the latest GitHub Blog, GitHub Changelog, and Awesome Copilot workflow content. Include source context when the update comes from the GitHub Blog, GitHub Changelog, or Awesome Copilot workflows.

Open a pull request for Mona to review. Use `safe-outputs` with `create-pull-request` so changes are proposed without writing directly to `main`. Keep the PR focused on Mona's GitHub Info updates and include a title that clearly references Mona or GitHub Info.
