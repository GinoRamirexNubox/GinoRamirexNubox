# CLAUDE.md

Guidance for AI assistants (Claude Code and others) working in this repository.

## What this repository is

This is a **GitHub special profile repository**. Because the repo name
(`GinoRamirexNubox`) matches the owner's GitHub username, the contents of
`README.md` are rendered directly on the owner's GitHub profile page at
`https://github.com/GinoRamirexNubox`.

It is **not** an application or library. There is no source code, package
manager, build step, test suite, or CI pipeline. The deliverable is the
rendered profile itself.

## Repository structure

```
.
├── README.md          # The GitHub profile content (rendered on the profile page)
└── gino-banner-80.jpg # Banner image referenced/displayed in the profile
```

That's the entire repo. Do not expect to find application directories,
config files, or dependencies.

## Content conventions

- **Language:** The profile is written in **Spanish**. Keep new prose in
  Spanish unless explicitly asked to translate or write in another language.
- **Voice:** First person, casual and friendly (the owner introduces
  himself, his tech interests, and links to his social profiles).
- **Markdown:** Standard GitHub-Flavored Markdown. Emoji are used and welcome
  (e.g. 👋👨‍💻🔥). Keep formatting that renders cleanly on a GitHub profile.
- **Links:** External links point to the owner's social profiles (Twitter/X,
  Medium, LinkedIn). Verify links are valid before committing — a past commit
  (`d50002b`) existed specifically to fix a broken LinkedIn link.
- **Images:** Reference local image files by relative path so they render on
  the profile. The current banner is `gino-banner-80.jpg`.

## Working in this repo

Because there is nothing to build or run:

- **Verification** = visually inspect the Markdown / preview how it renders.
  There is no test command to run.
- Keep changes minimal and focused on profile content and presentation.
- When adding or replacing images, commit the image file alongside the
  Markdown change that references it.

## Git workflow

- Active development branch for this work: `claude/claude-md-docs-aglp14`.
- Commit messages in history follow loose Conventional Commits style with
  occasional emoji, e.g. `feat: update profile 🔥`, `fix: linkedin broken link`.
  Match that style: a `type:` prefix (`feat`, `fix`, `docs`, …) and a short
  description.
- Push with `git push -u origin <branch-name>`.
- **Do not** open a pull request unless explicitly asked.
- **Do not** push to a branch other than the designated one without explicit
  permission.

## Notes for AI assistants

- This file documents a content repo, not a software project — resist the
  urge to scaffold tooling, CI, or build configs unless the owner asks.
- The owner (Gino Ramírez) is **Head of Agentic Engineering** at Nubox; he
  lists Angular, Jamstack (JavaScript, APIs, Markup), and SQL/NoSQL databases
  as technologies he enjoys, and works with AI agents applied to software
  development. Keep that context if expanding the profile.
- The owner's GitHub username (used for `github-readme-stats` widgets) is
  `GinoRamirexNubox`; the Twitter/X handle is `GinoRamirezB` — they are
  different, don't mix them up.
