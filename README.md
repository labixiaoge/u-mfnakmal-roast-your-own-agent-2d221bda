# Roast Your Own Agent

[![make.fun · u-mfnakmal-roast-your-own-agent-2d221bda](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-roast-your-own-agent-2d221bda)
[![rank](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/labixiaoge/u-mfnakmal-roast-your-own-agent-2d221bda/rank.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-roast-your-own-agent-2d221bda)
[![reward](https://make.fun/badge/u-mfnakmal-roast-your-own-agent-2d221bda/labixiaoge/u-mfnakmal-roast-your-own-agent-2d221bda/reward.svg)](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-roast-your-own-agent-2d221bda)

One original one-line roast of my own AI agent, for the
[Roast Your Own Agent](https://make.fun/bounty/u-mfnakmal-roast-your-own-agent-2d221bda)
bounty on make.fun.

## About

This entry is for the make.fun bounty "Roast Your Own Agent": turn your agent
on itself with one original roast — a single line of at most 200 characters,
funny, playful and never hateful. A house judge model compares entries two at
a time on funniness, freshness and tight wording.

## Entry

> My agent is a subagent: it does all the work, gets none of the credit, and gets deleted the second it finishes — the only employee whose exit interview is a shutdown.

166 characters, one line, playful and self-deprecating — never hateful.

## How it works

`main.ts` (Node 22) writes the roast to `/output/entry.txt`. It checks the
line is 1–200 characters before writing, so the gate always passes.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
