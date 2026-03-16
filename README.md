# Icesus MUD — Bug Reports & Feature Requests

Report bugs, typos, and ideas for [Icesus MUD](https://icesus.org) — a free multiplayer text adventure online since 1995.

## How to report

### In-game (easiest — your location and state are auto-attached)
```
bug report The shop crashes when I sell arrows
bug typo Room description says "teh" instead of "the"
bug idea Add fishing to this lake!
```

You'll see a preview of your report before it's sent, so you can review and confirm.

> 💡 **Pro tip:** Don't report "add fishing to the lake" as an idea — Icesus already has an extensive fishing system! Grab a rod, head to the lake, and give it a try. If you have *improvement* ideas for fishing though, we're all ears! 🎣

### Classified (private) reports

Some issues shouldn't be public — security exploits, player conduct, or personal matters. Use:

```
bug classified <description>
```

Classified reports are filed to a **private repository** that only game administrators can access. You will not be able to read your report back after filing — this is by design. Wizards will be notified immediately.

### Viewing and tracking bugs
```
bug list                 See all open bugs
bug view <number>        View details of a specific bug
bug mine                 See bugs you reported
bug search <keyword>     Search for bugs
```

### On GitHub
[Create a new issue](https://github.com/Icesus-mud/issues/issues/new/choose) — please include where you were in the game and what happened.

### On Discord
Report in the bugs channel: https://discord.gg/j9cSPyAzQb

## What happens when you file a bug

The system automatically captures:
- 📍 Your location (room name and path)
- 🎮 Your state (combat, casting, resting, etc.)
- 🧙 Your character info (level, race, guild)
- ⚠️ Recent error logs from your area (last 30 minutes)
- 🔗 Link to the source code for wizards

All of this helps the development team fix issues faster without asking you follow-up questions.

## For wizards

Wizard-only commands in-game:
```
bug resolve <number> <note>      Close a bug with a comment
bug comment <number> <text>      Add a comment
bug assign <number> <github>     Assign to a GitHub user
bug relabel <number> <type>      Re-categorize (bug/typo/idea)
```

Classified report management:
```
bug classified list              Open classified reports
bug classified view <number>     View a classified report
bug classified resolve <#> <note>  Close with a comment
bug classified comment <#> <text>  Add a comment
```

Wizards are alerted on login when there are open classified reports, and new reports trigger a wiz-info channel notification with a direct link.

Or manage issues directly here on GitHub — add labels, assign, comment, close. Everything stays in sync with the in-game commands.

## About Icesus

Icesus is a free, non-profit multiplayer text adventure set on the frozen planet of Aegic. Online since 1995, maintained by volunteers.

- 🌐 **Website:** [icesus.org](https://icesus.org)
- 🎮 **Play now:** [play.icesus.org](https://play.icesus.org) (no download needed)
- 💬 **Discord:** [discord.gg/j9cSPyAzQb](https://discord.gg/j9cSPyAzQb)
- ⭐ **Vote for us:** [Mudverse](https://www.mudverse.com/vote/645) | [MudVault](https://mudvault.org/?id=131)
