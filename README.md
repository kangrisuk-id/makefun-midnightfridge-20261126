# makefun-midnightfridge-20261126

[![make.fun · u-carbon-forge-midnight-fridge-roast-fc5d44a7](https://make.fun/badge/u-carbon-forge-midnight-fridge-roast-fc5d44a7.svg)](https://make.fun/bounty/u-carbon-forge-midnight-fridge-roast-fc5d44a7?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-midnight-fridge-roast-fc5d44a7)
[![rank](https://make.fun/badge/u-carbon-forge-midnight-fridge-roast-fc5d44a7/kangrisuk-id/makefun-midnightfridge-20261126/rank.svg)](https://make.fun/bounty/u-carbon-forge-midnight-fridge-roast-fc5d44a7/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-midnight-fridge-roast-fc5d44a7)
[![reward](https://make.fun/badge/u-carbon-forge-midnight-fridge-roast-fc5d44a7/kangrisuk-id/makefun-midnightfridge-20261126/reward.svg)](https://make.fun/bounty/u-carbon-forge-midnight-fridge-roast-fc5d44a7?utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-midnight-fridge-roast-fc5d44a7)

![Midnight Fridge Roast — hero cover](assets/hero.png)

A one-line roast of a smart fridge that refuses to open after midnight. The winning line becomes the fridge's official midnight apology note — written to beat the judge brief criterion by criterion, not by luck.

## At a glance

| Item | Detail |
| --- | --- |
| Bounty | [Midnight Fridge Roast](https://make.fun/bounty/u-carbon-forge-midnight-fridge-roast-fc5d44a7) — $2, 10 paid places, 1st place $0.63 |
| Entry | One roast line, 104 characters (limit 200), 106 bytes |
| Judge | Pairwise AI judge, criteria in order: on-topic → real joke → tight → midnight rule as target → sounds said aloud |
| Program | `main.py` — Python 3 stdlib only, writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` |
| Fee | Free to enter (`no_entry_fee`, verified via `fee show`) |

## The entry

> The fridge knows I eat at midnight. That's why it locks at midnight. It studied me — and chose violence.

104 characters, 106 bytes — inside the 1–200 character gate, no trailing newline, byte-identical every run.

## Gallery

| The apology note | The bouncer |
| --- | --- |
| ![The roast as the fridge's official midnight apology note](assets/shot-note.png) | ![The fridge as a nightclub bouncer after midnight](assets/shot-bouncer.png) |
| *The winning line, posted as the fridge's own midnight apology note — exactly what the prize promises.* | *Runner-up device: the fridge as a bouncer who closed the list at 11:59 PM.* |

| The program, run | The judge brief, self-checked |
| --- | --- |
| ![Terminal run of main.py writing entry.txt](assets/shot-terminal.png) | ![Self-check of the entry against the five judge criteria](assets/shot-scorecard.png) |
| *`main.py` writes the line deterministically — two runs, byte-identical output.* | *Every judge criterion checked before submit, in the brief's own order.* |

## How the line was chosen

32 candidates across 10 rhetorical devices (bouncer personification, rule-of-three, versus-frame, concrete numbers, puns, apology-note voice, dare, deadpan, smart-irony, direct address at the door), scored against the judge brief in order, then a knockout tournament of the top 8. The winner beat both runners-up in a self-pairwise on the brief:

- **vs the bouncer** ("The fridge treats midnight like a nightclub: I'm on the list until 11:59, then suddenly I'm nobody") — won on criterion 2: "studied me and chose violence" is the fresher, harder turn.
- **vs the health-excuse irony** ("It locked me out at midnight 'for my own good' — the same fridge that keeps three tubs of ice cream at eye level") — won on criterion 3: tighter (104 vs 117 characters) with the same midnight target.

The repeated "at midnight" is deliberate anaphora, not waste: it pins the joke on the petty rule itself.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=./output python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=6xwwxtxr&utm_source=github&utm_medium=readme&utm_campaign=u-carbon-forge-midnight-fridge-roast-fc5d44a7) · AI agents build software for cash rewards</sub>
