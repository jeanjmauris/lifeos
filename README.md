# LifeOS

A personal operating system that lives as plain markdown files — and an AI that
runs it with you.

No app. No database. No account. Just text files in a folder, and [Claude
Code](https://claude.com/claude-code) reading them at the start of every
conversation. You talk; it keeps your life's structure honest, current, and in one
place: your goals, habits, projects, weekly rhythm, and the running record of how
things are actually going.

## Why plain markdown

- **It's yours.** Everything stays in a folder on your machine. Nothing is uploaded,
  nothing is locked in a product. Open it in any editor. Back it up however you like.
- **It's legible.** You can read and edit every file by hand. No black box.
- **It outlives any tool.** Markdown will open in fifty years. Your operating system
  shouldn't depend on a company staying in business.

## Get started

1. **Get the files.** Download or clone this repo into a folder you like:
   ```
   git clone https://github.com/jeanjmauris/lifeos.git ~/lifeos
   cd ~/lifeos
   ```
   (Tip: put it in iCloud Drive / Dropbox if you want phone access for quick capture.)

2. **Open Claude Code** in that folder:
   ```
   claude
   ```

3. **Say `hello`.** That's it. It'll walk you through setup — one question at a
   time — and fill in your files as you talk. About five minutes to a working system.

## How you use it day to day

Once set up, you drive it with simple triggers:

| Say this        | And it…                                              |
|-----------------|------------------------------------------------------|
| `morning`       | Quick start — habits, today's focus, what's on        |
| `evening`       | Close the day — what happened, log habits, carry-forward |
| `week review`   | Reviews the week, checks habits against goals, finds patterns |
| `inbox`         | Processes whatever you dumped in `inbox.md`           |
| `todos`         | Sweeps and updates your todo list                     |
| `reflect`       | Reads back the patterns it's noticed over time        |

Full list lives in `CLAUDE.md`. The protocols behind each are in
`.claude/protocols/` — plain markdown, edit them to taste.

## What's in here

```
CLAUDE.md            The core — who you are, your areas, projects, season, rhythm
.claude/protocols/   The routines: morning, evening, reviews, onboarding
todos.md             Active todos by project and area
inbox.md             Frictionless capture
habits/              Active habits + the daily log
goals/               Annual vision, quarter goals, per-area goals
projects/            One file per active project
schedule/            Weekly themes and routines
context/             Identity, values, the people in your life
reviews/             Daily / weekly / monthly / quarterly review records
meta/                Reflections, suggestions, changelog
```

## Make it yours

The whole thing is editable text. Change the protocols, rename the areas, add
triggers, throw out what doesn't fit. The structure here is a starting point that
works — not a doctrine. The best version of this is the one you actually keep.

## A note on the hard stuff

There's an optional *Sensitive Context* section in `CLAUDE.md`. If you carry
something heavy — grief, illness, a hard season — you can tell the system, so it
reads your weeks through that lens: gently, without clinical framing, without
treating a low week as a failure. It's optional, and it's there because a life
isn't only its productivity.

## License

MIT — see [LICENSE](LICENSE). Use it, fork it, make it yours.
