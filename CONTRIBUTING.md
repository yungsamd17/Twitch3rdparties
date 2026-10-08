# Contributing

Thanks for helping keep this list accurate. Please read this guide before opening a pull request or issue.

## What to add

- Clients, mods, patches, web front-ends, browser extensions, ad-blocking tools, and other software for Twitch.
- Each entry must link to somewhere people can get or check the software: a repository, store page, or official website.
- Discontinued or unfinished projects are welcome. Mark them 🔴 so people know they exist and why they are not recommended.
- Do not add sites that only offer pre-modded APKs with no source, no maintainer, and no reports you can link to. If there are verified reports of malware or scams, add the entry with a ⛔ warning instead.

## Required fields

Every entry needs these columns:

| Field | What to write |
| ----- | ------------- |
| Name | The project name, linked to its repository or store page |
| Features | One or two short sentences about what it does. Keep it neutral; no marketing wording. |
| Language(s) | The language badges from [badges.md](badges.md). Use `[Closed source]` for closed-source software. |
| Development Status | One status symbol from the legend below, plus a short note if needed |

## Status legend

| Symbol | Meaning |
| ------ | ------- |
| 🟢 | Active |
| 🔵 | Active, but in beta / early / still in development |
| 🟠 | Slow, on hiatus, or activity not confirmed |
| 🔴 | Discontinued, archived, abandoned or outdated |
| ⛔ | Warning (malware risk, ToS risk, privacy concern) |

## Choosing a status

- Check the project's recent commits and releases yourself. Do not copy a status from an older list or from a README.
- Do not add version numbers or last-push dates to entries. They go out of date on every release, so the list would need constant edits.
- Describe the state with the symbol and, where it helps, a short qualifier such as "stable releases are outdated, use the dev build".
- If a project is still developed but its stable release is old, say so in the status note.
- If you are not sure, use 🟠 and say what you could not confirm.

## Warnings (⛔)

- Mark an entry with ⛔ instead of removing it. People should still be able to find it and see the warning.
- Give a reason in the status cell, for example "uses a third-party proxy", "may violate Twitch ToS", or "reported malware".
- Link to a source for the warning, such as a report, issue, store review, or official documentation.

## Opening a pull request

1. Fork the repository and create a branch for your change.
2. Keep each pull request to one entry or one status change.
3. Put the entry in the right section and table. Check the existing sections first.
4. In the pull request description, link to the project's repository or store page and say how you checked its status.
5. Use a short title such as `Add <Name>`, `Update status: <Name>`, or `Add warning: <Name>`.
6. Keep the wording neutral and factual.

## Removing entries

Open an issue or pull request that explains why the entry should go. Common reasons are that the project has been removed from all official sources and has no working build, or that it is confirmed to be malicious. Malware entries should normally stay with a ⛔ warning rather than being deleted.

## Language badges

- Use the badges already in [badges.md](badges.md).
- If a language is missing, add its badge to `badges.md` using the format described there, then use it in your entry.

## Reporting problems

If a link is broken, a status is wrong, or an entry is unsafe, open an issue. Include the entry name and the evidence you found.

## Code of conduct

Be respectful in issues and pull requests. Focus on the software and the evidence, not on the people who maintain it.
