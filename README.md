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

### Claude.ai / Claude desktop app
1. Download this repo as a ZIP (green **Code** button → **Download ZIP**), or grab `wwed.zip` from the Releases page.
2. In Claude, go to **Settings → Capabilities → Skills** and upload the `wwed` folder as a ZIP.
3. Make sure the skill is turned on.

### Claude Code
Copy the `wwed` folder into `~/.claude/skills/` (or your project's `.claude/skills/`).

## Use it

Type `/wwed` or just ask, for example:

> wwed: my cleaning business is stuck at 40 jobs a month, what's the bottleneck?

## Notes

- Quotes are short lines from Elon Musk's public interviews and talks. This project is not affiliated with or endorsed by Elon Musk, Tesla, or SpaceX.
- The skill flags where this way of thinking doesn't fit (small-budget risk, safety, legal, marketing).

## License

MIT
