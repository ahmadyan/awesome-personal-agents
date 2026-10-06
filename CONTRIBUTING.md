# Contribution Guidelines

Thanks for helping keep this list accurate. Please read this page before opening a pull request.

## What belongs here

A personal agent remembers the person it works for, keeps running between conversations, and acts for them across chat, files, and tools. An entry belongs here when it is one of the following:

- A personal agent or assistant, self-hosted or hosted, that keeps memory and can take actions, not only answer questions.
- A memory layer, runtime, sandbox, messaging bridge, front end, or integration that people use to build or run such agents.
- A paper, guide, or essay that explains how these agents work or how to run them safely.

It also has to be:

- Publicly available today, with a download, public documentation, or source code. Waitlists and private betas do not count yet.
- Maintained: the repository is not archived, the project has not announced that it is unmaintained or shutting down, and it has shipped a commit or release in roughly the last six months. Papers and essays are exempt from the activity rule.
- The official project, not a mirror, a rebrand of someone else's work, or a fork without meaningful changes of its own.

Chat-only front ends without agent features, general LLM frameworks, and prompt collections belong elsewhere.

## Entry format

Add one line to the section that fits best:

```markdown
- [Name](https://link.to/official/site-or-repo) - What it does and who makes it, in one or two plain sentences. Open source (MIT).
```

- Link to the official repository, product page, or documentation.
- Write the description yourself. Describe what it does; leave out superlatives, rankings, pricing claims, and benchmark numbers.
- Label software as `Open source (SPDX-ID)`, `Source-available (license name)`, or `Proprietary`. Reading entries skip the label and name the author or publisher.
- Add `macOS` when a tool only runs on a Mac.
- Mention data handling only when it is documented, for example where memory is stored or whether a relay can read messages.
- Keep entries alphabetical within the section (case-insensitive). Descriptions start with a capital letter and end with a period.

## Pull requests

- One entry per pull request. Separate pull requests are easier to review and to revert.
- Use the entry's name as the pull request title, and say in the body why it belongs here.
- Check that every link resolves and that the repository is not archived.
- Run `npx awesome-lint` before you push.

## Corrections and removals

Open an issue or a pull request when a link breaks, a project is renamed, archived, or shut down, or a description has gone stale. Removing dead entries is as useful as adding new ones.
