# WWED — What Would Elon Do

A Claude skill that takes any situation (a business, a project, a process) and finds the **one limiting factor** slowing it down, using first-principles thinking and Elon Musk's 5-step "algorithm" (question requirements → delete → simplify → accelerate → automate).

It's an analysis tool, not a roleplay. Claude won't pretend to be Elon.

## What you get

- Your goal as one real number
- The chain of steps that produce it, with rates and capacity
- The single bottleneck, and a test to prove it's the real one
- How to clear it, in the right order
- One action for the next 24 hours, and the number that proves it worked
- What to stop doing

## Install

### Claude directory
Find **WWED** in Claude under **Customize → Skills/Plugins** and click **Add** (once the listing is approved).

### Manual (Claude.ai / desktop app)
1. Download this repo (green **Code** button → **Download ZIP**).
2. Zip the `skills/wwed` folder and upload it in **Customize → Skills → Add**.

### Claude Code
```
/plugin install wwed --marketplace liamgg707-debug/wwed
```
Or copy `skills/wwed` into `~/.claude/skills/`.

## What it sends or runs

Nothing. This plugin is a single instruction file (`skills/wwed/SKILL.md`). It runs no code, calls no servers, and stores no data.

## Use it

Type `/wwed` or just ask, for example:

> wwed: my cleaning business is stuck at 40 jobs a month, what's the bottleneck?

## Notes

- Quotes are short lines from Elon Musk's public interviews and talks. This project is not affiliated with or endorsed by Elon Musk, Tesla, or SpaceX.
- The skill flags where this way of thinking doesn't fit (small-budget risk, safety, legal, marketing).

## License

MIT
