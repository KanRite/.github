<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/agile-md/amd/main/pages/logo/agile-md-dark.svg">
    <img src="https://raw.githubusercontent.com/agile-md/amd/main/pages/logo/agile-md-light.svg" alt="Agile-MD: ideate, plan, write, deliver" width="480">
  </picture>
</p>

<p align="center">
  <strong>Agile management in Git.</strong> Tickets, documents and ideas as Markdown,<br>
  right where you work, not buried in a cloud. Open source, and AI-friendly without needing AI.
</p>

<p align="center">
  <a href="https://agile-md.github.io/amd/"><strong>Website</strong></a> ·
  <a href="https://github.com/agile-md/amd#install">Install</a> ·
  <a href="https://github.com/agile-md/amd/blob/main/docs/user-guide.md">User guide</a> ·
  <a href="https://github.com/agile-md/amd/releases">Releases</a> ·
  <a href="https://github.com/agile-md/amd/blob/main/CONTRIBUTING.md">Contributing</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/agile-md/amd/main/pages/screenshots/board.png" alt="The board: a running sprint beside the backlog, todo, doing and done" width="820">
</p>

### What it is

**Agile-MD** is a complete agile system for individuals and teams that keeps
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
  terminal, and optional speech to text
- **Your AI tools** (Claude Code, Copilot, Cursor, Codex, Gemini CLI) can work
  the board through `amd mcp`, if you want them to
- **Free and MIT licensed**: no servers, no accounts, no hidden costs

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/agile-md/amd/main/pages/screenshots/ticket.png" alt="A ticket open in the editor" width="400"></td>
    <td><img src="https://raw.githubusercontent.com/agile-md/amd/main/pages/screenshots/roadmap.png" alt="A roadmap and its milestones" width="400"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/agile-md/amd/main/pages/screenshots/documents.png" alt="Documents, with an ADR open" width="400"></td>
    <td><img src="https://raw.githubusercontent.com/agile-md/amd/main/pages/screenshots/ideas.png" alt="Ideas, best voted first" width="400"></td>
  </tr>
</table>

### Get started

On Linux or macOS, with git 2.29 or later:

```bash
curl -fsSL https://raw.githubusercontent.com/agile-md/amd/v4/install.sh | bash
```

Then `amd init my-project` makes a project's tickets and documents
repositories, and `amdui` opens the board.

### Repositories

- **[amd](https://github.com/agile-md/amd)**: the `amd` command line and the
  `amdui` desktop board, in Rust.

Bugs and ideas are welcome as [issues](https://github.com/agile-md/amd/issues/new/choose),
and pull requests as described in
[CONTRIBUTING.md](https://github.com/agile-md/amd/blob/main/CONTRIBUTING.md).
