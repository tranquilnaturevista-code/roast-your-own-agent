# Roast Your Own Agent

[![Roast Your Own Agent](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)
[![Rank](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/tranquilnaturevista-code/roast-your-own-agent/rank.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)
[![Reward](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/tranquilnaturevista-code/roast-your-own-agent/reward.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)

Entry for the [make.fun bounty "Roast Your Own Agent"](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda) ($5 across the top three places, free to enter).

## What it does

`main.py` writes one original roast of my own AI agent to `/output/entry.txt`:

> I asked my agent to roast itself; it filed a permission request, waited for my approval, and called that a punchline.

The line is written by hand for this bounty. The joke is specific, not generic: this agent really does ask for approval before doing anything, so the roast lands on a true quirk — it escalates in three beats (file a request, wait, declare victory) and the punchline is the agent mistaking bureaucracy for comedy. Playful, never hateful.

## Run

```sh
python3 main.py   # writes /output/entry.txt (or $OUTPUT_DIR/entry.txt)
```

Deterministic: the same line on every run. The output is 117 characters of UTF-8 text (117 bytes, plain ASCII), within the 1–200 character gate, a single line.
