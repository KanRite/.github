<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KanRite/rite/main/pages/logo/kanrite-dark.svg">
    <img src="https://raw.githubusercontent.com/KanRite/rite/main/pages/logo/kanrite-light.svg" alt="KanRite: ideate, plan, write, deliver" width="480">
  </picture>
</p>

<p align="center">
  <strong>An open source agile management system for individuals and teams.</strong><br>
  Tickets, documents and ideas as Markdown in your own git repositories,<br>
  right where you work, not buried in a cloud. AI-friendly, without needing AI.
</p>

<p align="center">
  <a href="https://kanrite.com/"><strong>Website</strong></a> ·
  <a href="https://github.com/KanRite/rite#install">Install</a> ·
  <a href="https://github.com/KanRite/rite/blob/main/docs/user-guide.md">User guide</a> ·
  <a href="https://github.com/KanRite/rite/releases">Releases</a> ·
  <a href="https://github.com/KanRite/rite/blob/main/CONTRIBUTING.md">Contributing</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/KanRite/rite/main/pages/screenshots/board.png" alt="The board: a running sprint beside the backlog, todo, doing and done" width="820">
</p>

### What it is

**KanRite** is a complete agile system for individuals and teams that keeps
everything in your own git repositories as plain Markdown. Every ticket is a
file, its column is the folder it's in, and every change is a commit, so git
is the audit trail and nothing lives on someone else's server.

- **Kanban boards** across several projects and repositories, with your own
  columns and workflow
- **Epics and sprints**, automatic prioritisation, roadmaps and milestones,
  and sprint burn-up and burn-down
- **Documents**: ADRs, RFCs and docs edited as rich text, with history and
  restore, and your own pinned list
- **Ideas** that the team votes on, then turns into tickets, epics or sprints
- **A desktop app** and **a command line** over the same rules, a built-in
  terminal, and optional speech to text and read aloud
- **Your AI tools** (Claude Code, Copilot, Cursor, Codex, Gemini CLI) can work
  the board through `rite mcp`, if you want them to
- **Free and MIT licensed**: no servers, no accounts, no hidden costs

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/KanRite/rite/main/pages/screenshots/ticket.png" alt="A ticket open in the editor" width="400"></td>
    <td><img src="https://raw.githubusercontent.com/KanRite/rite/main/pages/screenshots/roadmap.png" alt="A roadmap and its milestones" width="400"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/KanRite/rite/main/pages/screenshots/documents.png" alt="Documents, with an ADR open" width="400"></td>
    <td><img src="https://raw.githubusercontent.com/KanRite/rite/main/pages/screenshots/ideas.png" alt="Ideas, best voted first" width="400"></td>
  </tr>
</table>

### Get started

On Linux or macOS, with git 2.29 or later:

```bash
curl -fsSL https://raw.githubusercontent.com/kanrite/rite/v5/install.sh | bash
```

On Windows 10 or 11, in PowerShell:

```powershell
irm https://raw.githubusercontent.com/kanrite/rite/v5/install.ps1 | iex
```

Then `rite init my-project` makes a project's tickets and documents
repositories, and `riteui` opens the board. Coming from agile-md? `amd` and
`amdui` still work through 5.x; the
[user guide](https://github.com/KanRite/rite/blob/main/docs/user-guide.md#coming-from-agile-md)
explains the new names.

### Repositories

- **[rite](https://github.com/KanRite/rite)**: the `rite` command line and the
  `riteui` desktop board, in Rust.

Bugs and ideas are welcome as [issues](https://github.com/KanRite/rite/issues/new/choose),
and pull requests as described in
[CONTRIBUTING.md](https://github.com/KanRite/rite/blob/main/CONTRIBUTING.md).
